# steps followed

Created a new repository from Terminal.

1. Install git CLI to use gh commands in VS code Terminal.
   a. Install by downloading msi file.
   b. Then restart your VS code to reflect changes.
2. Opened the folder of our React app in Terminal = **Most Important step XD**
   Did the initialization of files here.

   a. _git init -b main_
   b. _git add ._
   c. _git commit -m "tutorial commit 1"_

   Note - this should have been the third step.

3. Created repository on github.com with the same name "tutorial" using VSC Terminal.
   a. ran the command _gh repo create_
   b. It asks whether we want to create a new repository or push the local one. Chose to add a new repository.
   Note: For pushing the local one, always type **.**. This will help push our local repository.
   c. It asked to create a Readme.md file, but I created a _.gitignore_ from the options.

4. Added and removed and then again added remote origin. It was not working as I added the SSH one. Must add the HTTPS. So copied the https version and added the remote repository

5. Tried doing recommit, but Here no commit is possible, as no files have changed.

6. Tried pushing the local repository but couldn't.
   Command used - _git push -u origin main_

7. Again executed command _gh repo create_
   a. In this step, did the above mentioned Step _3.b.Note_.
   b. Again tried to push repository but couldn't.

8. Cmd executed _git pull_, then again tried _git push -u origin main_. But failed again.
9. Finally did force push - _git push -f origin main_. Successfull this time.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
