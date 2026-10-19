# Carlos P. Garcia Attendance

Static HTML prototype for the QR-ID Attendance Monitoring System for Carlos P. Garcia Senior High School.

## Deploy to Vercel

1. Create a GitHub repository named `carlos-p-gracia-attendance`.
2. Upload `index.html`, `vercel.json`, and this `README.md` to the repository root.
3. In Vercel, choose **Add New → Project** and import the GitHub repository.
4. For a plain static HTML site, leave the framework preset as **Other** and leave the build command and output directory empty/default unless Vercel asks otherwise.
5. Click **Deploy**.

The entry point is `index.html` at the repository root.

## Important prototype note

This is a browser-side prototype. Data saved with `localStorage` is local to each browser and is not shared between teachers, students, and administrators across different devices. Do not use real student LRNs, ID photos, passwords, or sensitive attendance records in this prototype. A production school system needs a secure backend and database.
