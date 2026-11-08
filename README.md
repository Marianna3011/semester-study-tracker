# Semester study tracker

A small static website for keeping semester courses, assignment deadlines, notes, and task status together. It starts with the courses and tasks from the linked UNI sheet.

## Open it

Open `index.html` in a current browser. No install, account, or server is required. The first load creates the starter semester; changes are saved in that browser using local storage.

## Use it

- Add, edit, complete, or remove tasks from Overview, All tasks, or Calendar. The All tasks page includes a table with editable To do, In progress, Waiting, and Done statuses.
- Filter or search tasks by course and status.
- Use Calendar for a monthly deadline view and the weekly class pattern read from USOS. The timetable marks alternating odd/even week groups and shows the listed start time and room.
- Add and remove courses in Courses.
- Store a source URL on each task to open its eKursy/GitHub reference.
- Use **Download backup** before changing browser/device; **Restore backup** imports that JSON file.
- Edit the semester name and dates in `app.js` in the `initial.term` object when reusing it for another term. Update the starter course/task lists there too.

The app is a local tracker. It does not sync changes back to Google Sheets, eKursy, or USOS. The spreadsheet and USOS plan remain linked as sources of record. Some source-sheet deadline notes conflict; those are preserved in the task notes for confirmation. GitHub Pages can publish the app so it opens from a link, but it is public and local-browser changes do not sync between devices by themselves.

