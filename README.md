AttendSure 📊

AttendSure is a modern, mobile-first student attendance management web app designed to help college and university students manage their class schedules, track attendance, analyze academic performance, and generate attendance reports.

🚀 Live Demo

Add your GitHub Pages URL here after deployment:

Live Demo: https://github.com/aasis161101-cloud/attendsure.git

✨ Features
🏠 Dashboard
View today's classes.
See the current or next class.
Quickly check in for a class.
View overall attendance percentage.
View today's attendance statistics.
Get warnings when attendance falls below the target percentage.
📅 Timetable Management
View your weekly timetable.
Add classes.
Edit classes.
Delete classes.
Configure:
Subject
Teacher
Day
Start time
End time
Room
Lecture/Practical type
✅ Attendance Tracking
Mark classes as Present.
Mark classes as Missed.
Automatically identify missed classes.
Edit attendance records.
View complete attendance history.
Filter attendance history by subject.
Filter attendance history by status.
📈 Analytics

AttendSure provides visual attendance analytics, including:

Subject-wise attendance.
Present vs. absent distribution.
Weekly attendance trends.
Monthly attendance trends.

Charts are powered by Chart.js.

📄 PDF Reports

Generate downloadable attendance reports using jsPDF.

Supported reports:

Weekly attendance report.
Monthly attendance report.
Complete semester attendance report.

Reports include:

Student information.
College.
Course.
Semester.
Subject-wise attendance.
Overall attendance percentage.
👤 Profile & Settings

Customize your:

Name.
College.
Course.
Semester.
Attendance target.
Semester start date.
Attendance calculation method.
Notification preferences.
Reminder timing.
Theme.
🔔 Class Reminders

AttendSure supports browser notifications for upcoming classes.

Available reminder intervals:

5 minutes before class.
10 minutes before class.
15 minutes before class.
30 minutes before class.
🌙 Dark Mode

Three appearance modes are available:

Light.
Dark.
System.
💾 Data Storage

AttendSure stores application data locally.

The application supports:

window.storage when running in a supported artifact environment.
localStorage when running as a standalone website.

Stored information includes:

Timetable.
Attendance records.
Profile settings.
Attendance preferences.
🛠️ Technologies Used
Technology	Usage
HTML5	Application structure
CSS3	UI, responsive design and themes
JavaScript	Application functionality
Chart.js	Attendance charts
jsPDF	PDF report generation
Google Fonts	Application typography
LocalStorage	Local data persistence
📱 UI Design

AttendSure uses a mobile-first design optimized for small screens.

The interface includes:

Responsive cards.
Bottom navigation.
Mobile-friendly controls.
Interactive timetable.
Attendance dashboard.
Dark mode.
Modern typography.
Responsive charts.
Mobile safe-area support.

The application has a maximum content width of 480px, giving it an app-like appearance on mobile devices.

📂 Project Structure
AttendSure/
│
├── index.html
├── icon.svg
└── README.md

Files

index.html

Contains the complete AttendSure application, including:

HTML structure.
CSS styles.
JavaScript logic.
Timetable.
Attendance engine.
Analytics.
PDF export.
Settings.
Local storage.

icon.svg

Application favicon and mobile app icon.

README.md

Project documentation.

💻 Installation

No backend or database server is required.

Clone the repository
git clone https://github.com/YOUR-USERNAME/attendsure.git


Navigate into the project:

cd attendsure


Open index.html in your browser.

🧑‍💻 Run Locally

You can simply open:

index.html


in a modern web browser.

For development, you can also use VS Code Live Server or another local HTTP server.

Example:

python -m http.server 8000


Then open:

http://localhost:8000

🌐 Deploy with GitHub Pages

AttendSure can be deployed directly through GitHub Pages.

1. Create a repository

Create a GitHub repository named:

attendsure

2. Upload the files

Upload:

index.html
icon.svg
README.md

3. Enable GitHub Pages

Go to:

Settings → Pages


Under Build and deployment, select:

Source: Deploy from a branch
Branch: main
Folder: / (root)


Click Save.

Your application will then be available at:

https://YOUR-USERNAME.github.io/attendsure/

📊 Attendance Calculation

The default attendance calculation is:

Attendance % = (Present Classes / Total Classes) × 100


For example:

Present Classes = 18
Total Classes   = 20

Attendance = (18 / 20) × 100

Attendance = 90%


The application provides additional calculation settings for:

Standard calculation.
Practical classes counted double.
Lectures only.
🎯 Attendance Target

The default attendance target is:

75%


The target can be changed from:

Profile → Attendance Rules


Subjects below the configured target are highlighted on the dashboard.

🔔 Notifications

AttendSure uses the browser's Notification API for class reminders.

Users must grant notification permission for browser notifications to work.

Notifications are best-effort and may depend on browser permissions, browser settings, and whether the application is currently running.

🔐 Privacy & Data

The current version of AttendSure does not require a backend server or user account.

When running standalone, data is stored in the browser using localStorage.

Therefore:

Clearing the browser's site data may permanently remove locally stored attendance information.

A future cloud-backed version could provide secure authentication and synchronization across devices.

📚 Default Timetable

The application includes a sample timetable with subjects such as:

French-I
English
Digital Logic Design
Programming for Problem Solving
Discrete Mathematical Structures
Verbal Ability and Skills Development

The timetable can be modified from the Timetable section.

🔮 Future Improvements

Possible future features include:

 Progressive Web App (PWA) support.
 Offline support.
 Cloud synchronization.
 User authentication.
 Firebase/Supabase backend.
 Cross-device synchronization.
 Automatic timetable import.
 Calendar integration.
 Attendance prediction.
 Attendance shortage calculator.
 "How many classes can I miss?" calculator.
 "How many classes do I need to attend?" calculator.
 Subject-specific attendance targets.
 CSV/Excel export.
 Improved notification scheduling.
 Multiple student accounts.
 Faculty/admin dashboard.
🤝 Contributing

Contributions are welcome!

Fork the repository

Create your own fork of the project.

Create a feature branch
git checkout -b feature/new-feature

Make your changes

Implement your feature or fix.

Commit your changes
git add .
git commit -m "Add new feature"

Push your branch
git push origin feature/new-feature


Then open a Pull Request on GitHub.

🐛 Bug Reports

If you find a bug, please open a GitHub Issue.

Include:

Browser and version.
Operating system.
Device.
Steps to reproduce.
Expected behavior.
Actual behavior.
Screenshot, if possible.
⭐ Support

If you find AttendSure useful, consider giving the repository a ⭐ Star on GitHub.

📜 License

This project is licensed under the MIT License.

See the LICENSE file for more information.

👨‍💻 Author

AttendSure

A student-focused attendance management application built with:

HTML • CSS • JavaScript • Chart.js • jsPDF

📌 Project Status

Status: 🟢 Active Development

AttendSure is currently a client-side web application. More features and improvements may be added in future releases.

Made with ❤️ for students

AttendSure — Track attendance. Stay on track.
