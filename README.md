<img width="1362" height="624" alt="shecan1" src="https://github.com/user-attachments/assets/864b2134-65f4-478e-8562-ab6ca1c39fd7" />
<img width="1340" height="600" alt="shecan2" src="https://github.com/user-attachments/assets/2ced5f22-ca06-43ae-a641-d8110eb6289c" />
<img width="1334" height="574" alt="shecan3" src="https://github.com/user-attachments/assets/a93b58ff-c40c-4115-8baa-b5492ad52dd0" />
# she-can-app
👩‍💻 She Can Foundation Member AppA simple and elegant web app for managing foundation members.This single-page application provides a straightforward way for the She Can Foundation to manage its members. It's built for seamless data handling and a great user experience on any device, using Firebase as a robust, real-time backend.✨ FeaturesMember Cards: Visually appealing cards display each member's name and bio.Add New Members: A clean, easy-to-use form to add new members to the database.Real-Time Sync: Data is instantly synchronized across all devices using Firestore.Fully Responsive: Looks and works great on mobile phones, tablets, and desktops.🚀 Get StartedFollow these steps to get the app running on your local machine or deployed live.1. ⚙️ PrerequisitesA Firebase project is required.The Firebase CLI is needed for deployment to Firebase Hosting (npm install -g firebase-tools).2. 🔑 Firebase ConfigurationOpen the project's index.html file.Locate the following line within the <script type="module"> tag:const firebaseConfig = typeof __firebase_config !== 'undefined' ? JSON.parse(__firebase_config) : {};
Replace this entire line with your unique firebaseConfig object, which you can find in your Firebase project console. Your code should then look like this:const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
3. 🏃‍♂️ Run LocallyThe easiest way to run the app is using the Live Server extension in VS Code.Right-click index.html and select "Open with Live Server".4. 🌐 DeploymentYou have two excellent, free options for making your app live:Firebase Hosting: The most seamless option. Use the Firebase CLI to deploy your app with one command.GitHub Pages: A great alternative for hosting static sites directly from this repository. Make sure the repository is public and enable the feature in your repository's Settings > Pages menu.💻 TechnologiesThis project is built using modern, lightweight technologies:HTML, CSS, JavaScriptTailwind CSS - Utility-first styling for a beautiful, responsive UI.Firebase Firestore - A powerful, real-time NoSQL database.
