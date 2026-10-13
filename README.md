FLAT Studyspace 📚

A personal study dashboard for Formal Languages and Automata Theory (FLAT). FLAT Studyspace helps students organize their syllabus, track topic completion, plan study sessions, and revise in one place.

Current version: Standalone HTML prototype. It runs in a browser without installing Node.js or configuring a backend.

✨ Features

Dashboard: See your study progress at a glance.

Syllabus tracker: Mark topics as completed and monitor progress.

Tasks and deadlines: Keep track of study tasks.

Calendar: Organize study plans and important dates.

Focus room: Use a focus timer for study sessions.

Quick revision: Review topics and flashcards.

Study notes: Write and save your own notes.

Theme toggle: Switch between light and dark themes.

Backup and restore: Export your browser-stored data and import it later.

Topic search: Find FLAT explanations on YouTube.

🧰 Built With

HTML5

CSS3

JavaScript

Browser localStorage

Google Fonts

📁 Repository Structure

For the current standalone website, keep the repository simple:

flat-studyspace/
├── index.html          # Main website
├── README.md           # Project documentation
├── assets/
│   ├── images/         # Screenshots, icons, and other images
│   └── favicon.png     # Optional browser icon
├── docs/
│   └── screenshots/    # Optional project screenshots
└── LICENSE             # Optional license file

Where should the website file go?

Rename your current flat_study_tracker_blue.html (or whichever version you want to publish) to index.html and put it in the root of the repository. If your website is a single HTML file with its CSS and JavaScript inside it, you do not need src/, package.json, or node_modules/.

🚀 Run Locally

Download or clone this repository.

Open index.html in your browser.

Start using the study dashboard.

No build step is required for the standalone version.

🌐 Publish with GitHub Pages

Push the repository to GitHub.

Open the repository on GitHub.

Go to Settings → Pages.

Under Build and deployment, choose Deploy from a branch.

Select the main branch and the / (root) folder.

Save and wait for GitHub Pages to publish the site.

Open the published URL shown in the Pages section.

GitHub Pages is suitable for this static HTML version. It does not run a backend server.

💾 How Data Is Saved

This version uses the browser's localStorage to save supported study data on the current browser and device.

Data is not automatically synced between devices.

Clearing browser storage may remove saved data.

Use the website's export/backup feature regularly.

Import a backup to restore data in the same or another compatible browser.

⚠️ Current Limitations

This standalone version does not include a live database or cross-device synchronization.

The AI Study Buddy, if included in this version, prepares a prompt for copying into an AI assistant. It does not itself connect to a live AI model.

YouTube topic buttons open search results. They are not necessarily direct links to individually verified videos.

🛣️ Future Improvements

Move the interface into reusable React components.

Add Supabase authentication and a PostgreSQL database.

Sync notes, tasks, and progress across devices.

Add a real AI tutor through a secure server-side function.

Improve accessibility and add automated tests.

🔐 Security Notes

Never commit passwords, API keys, .env files, or Supabase service-role/secret keys to GitHub.

If a React + Supabase version is added later, commit only a safe .env.example with placeholder values.

🤝 Contributing

Suggestions and improvements are welcome. Open an issue to report a bug or propose a feature, or submit a pull request.

📄 License

Choose a license before allowing others to reuse or modify the project. If you want a simple, permissive open-source option, consider the MIT License and include its full text in a LICENSE file.

Made for focused study, one topic at a time. 🌱
