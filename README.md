# YouTube Clone App

This is a YouTube clone app created using React and powered by the YouTube API from RapidAPI. You can use this app to search for YouTube videos and watch them within the application.

## Running Locally

To run this application locally, follow these steps:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/blazerrt86899/youtube-clone-react.git
   ```
2. Navigate into the project directory:
   ```bash
   cd your-repo
   ```
3. Install the dependencies using npm or yarn:
   ```bash
   npm install
   # or
   yarn install
   ```
4. Create a `.env` file in the root directory and add your RapidAPI YouTube API key:
   ```bash
   REACT_APP_YOUTUBE_API_KEY=YOUR_API_KEY
   ```
5. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```
6. Open your browser and navigate to `http://localhost:3000` to view the app.

## Deploying to Netlify

To deploy this application to Netlify, you can follow these steps:

1. Sign up for a free account on [Netlify](https://www.netlify.com/) if you haven't already.
2. Install the Netlify CLI globally using npm:
   ```bash
   npm install -g netlify-cli
   ```
3. Navigate into your project directory:
   ```bash
   cd your-repo
   ```
4. Build your React app for production:
   ```bash
   npm run build
   # or
   yarn build
   ```
5. Log in to Netlify using the CLI and follow the prompts to authorize the application:
   ```bash
   netlify login
   ```
6. Deploy your app to Netlify:
   ```bash
   netlify deploy --dir=build
   ```
7. Follow the prompts to set up the deployment options and confirm the deployment.

Your app should now be deployed to Netlify, and you will receive a URL where you can access it.

## Notes

- Ensure you have Node.js and npm (or yarn) installed on your machine before running the application.
- Make sure to replace `YOUR_API_KEY` with your actual RapidAPI YouTube API key in the `.env` file.
- Remember to keep your API key secure and avoid sharing it publicly.
