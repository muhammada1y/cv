#  this cv Create through React App

follow these command for run react app

# clone this repo
git clone https://github.com/muhammada1y/cv.git

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### if app run through Docker
### `follow the command`

#first build docker image 
docker build -t my-react-app .
#then run that image
docker run -p 3000:3000 my-react-app

**then it will be run on container id and port 3000**





