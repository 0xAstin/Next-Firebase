# Next.js Firebase Project

This is a starter template for a Next.js project with Firebase integration. This project is designed to help you get started quickly with building a server-side rendered application using Next.js and Firebase.

## Getting Started

### Prerequisites

To get started with this project, you will need to have the following installed:

- Node.js (version 10.13 or later)
- npm or Yarn
- Firebase CLI (if you plan to use Firebase functions or deploy to Firebase hosting)

### Installation

To install this project, you can either clone the repository or use the template feature on GitHub.

Clone the repository using:

git clone https://github.com/your-username/next-firebase-project.git

Or use the template feature on GitHub:

1. Click on the "Use this template" button at the top of the repository page.
2. Follow the instructions to create a new repository from the template.

Once you have the project on your machine, install the dependencies using npm or Yarn:

npm install

or

yarn install

### Configuration

This project uses Firebase for authentication and database. You will need to set up a Firebase project and configure the app with your Firebase credentials.

1. Go to the Firebase Console and create a new project.
2. In the project settings, click on "Add app" and select "Web".
3. Follow the instructions to register your app and generate a Firebase configuration object.
4. Copy the Firebase configuration object and paste it into the .env.local file in the project root directory.

FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_auth_domain
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
FIREBASE_APP_ID=your_app_id

5. Enable the Firebase Authentication and Firestore services in your Firebase project.
6. (Optional) If you plan to use Firebase functions or deploy to Firebase hosting, you will need to initialize Firebase in your project directory by running firebase init.

### Development

To start the development server, run:

npm run dev

or

yarn dev

This will start the Next.js development server with hot reloading enabled.

### Deployment

To build and deploy the project, you can use the Firebase CLI:

1. Run npm run build or yarn build to build the production version of the app.
2. Run firebase login to log in to your Firebase account.
3. Run firebase init to initialize Firebase in your project directory (if you haven't done so already).
4. Run firebase deploy to deploy the app to Firebase hosting.

### Additional Resources

- Next.js Documentation: https://nextjs.org/docs/getting-started
- Firebase Documentation: https://firebase.google.com/docs
