# APPLYING DEVOPs SKILLS ON THE REACT-VITE STARTER APPLICATION
With this repository, I describe my journey l

## FIRST TASK: CONFIGURE AND DEPLOY THE APPLICATION USING FIREBASE
1. `firebase login`
    1. if firebase command not recognised, then install firebase
        1. `npm install -g firebase-tools` (-g) makes the installation global.
2. `firebase login` should work now.
    1. if successfully logged in, then move on to the next
3. initiallize firebase in the project, select hosting, and what the public directory would be using `firebase init` 
    it was important i make a choice of firebase hosting instead of firebase app hosting, since my application is a pure react app (front-end app) that does not include any backend service

4. build the app, using 
    1. `npm run build`
5. deploy using `firebase deploy`

### RESULTS:
the hosting URL of the deployed application
https://react-firebase-b1434.web.app/ 