# MyTrack — Personal Academic & Life Progress Tracker

A local-first Next.js app for tracking academic progress, assignments, experiments, syllabus completion, seminars, events, projects, exams and notes.

## Included
- Dashboard with pending/submitted/overdue counts and average syllabus progress
- Subjects: syllabus %, experiments covered and total experiments
- Assignments/projects: deadline + submission status + submission date
- Seminars: topic and deadline
- Events: date, role and notes
- Exam dates and topics can be added by extending the same record model
- Notes
- Search
- JSON backup/restore
- Browser localStorage persistence
- Responsive mobile layout

## Run
```bash
npm install
npm run dev
```
Then open http://localhost:3000

## Next upgrades
1. Add exam CRUD screen with topic checklist.
2. Add calendar view.
3. Add file attachments for notes and submissions.
4. Add recurring reminders / notifications.
5. Add Supabase authentication + cloud sync if multi-device storage is needed.
