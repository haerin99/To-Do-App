# To-Do-App

Organize daily tasks and track habits.

## Features
### Login
- Email address and password
- Google authentication

### 4 tabs
**Tasks**
- Dark and light modes
- Add sections
- Filter: All, Habits, To-Dos, and Recurring.

**Inbox**
- Toggle to sort by label
- Move tasks from Inbox to Tasks (a particular section or no section)

**Labels**
- Choose from 9 possible colors

**Habits**
- Set the daily reset time. Habits and recurring tasks will be unchecked at this time every day.
- Grid tracker for the past 6 months
- Streak counter
- Linked to Tasks and Inbox. Deleting a task marked as a habit in Tasks/Inbox will delete it from Habits, and vice versa.

When adding a task, you can select its location as either Tasks (a particular section or no section) or Inbox. When editing a task, you can change its location, toggle Habit or Recurring, select a label, and add subtasks. Drag-and-drop and keyboard shortcuts (copy, paste, select one, select a range, esc, and delete) are available.

<img width="615" height="667" alt="Screenshot 2026-05-14 at 4 16 13 PM" src="https://github.com/user-attachments/assets/98d9fb23-d956-48bc-be32-c85830f54d9e" />

<img width="627" height="683" alt="Screenshot 2026-05-14 at 4 18 33 PM" src="https://github.com/user-attachments/assets/9f0743ea-7e25-48bc-87fa-643632aae686" />

<img width="1219" height="679" alt="Screenshot 2026-05-14 at 4 16 32 PM" src="https://github.com/user-attachments/assets/1ba74322-9224-44af-bd8d-341fb2c3f2d5" />

<img width="621" height="681" alt="Screenshot 2026-05-14 at 4 17 01 PM" src="https://github.com/user-attachments/assets/170a3400-7a7d-46fc-a1a1-b1ff3d5e5bdf" />

<img width="1250" height="1374" alt="image" src="https://github.com/user-attachments/assets/fd88bc4f-8399-4168-b790-11ccf43a1772" />


## Set up
Google authentication.
1. Create a project on Firebase Console (console.firebase.google.com). Add a web app.
2. Under Product categories, set up the following.
   - Security > Authentication
   - Databases & Storage > Firestore
3. Go to Settings > General. Scroll down and copy const firebaseConfig, including brackets. Download the HTML file from this repository. Replace the const firebaseConfig (lines 701-709) in the file with the one you copied.

Host the website for free.
1. Create a project on Netlify (netlify.com).
2. In Project overview, drag your HTML file to the appropriate space under Production deploys.
3. Now you can start using your website.

You can use websites other than Firebase Console and Netlify to set up Google authentication and to host the website.
