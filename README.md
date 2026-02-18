# Simple Chat Agent (v16)

A minimal chat agent that uses the Gemini API.

## Deployment on Render

1. Create a new "Web Service" on Render.
2. Connect this GitHub repository.
3. Set the following environment variable:
   - `GEMINI_API_KEY`: Your Google Gemini API Key.
4. Render will automatically detect the `package.json` and start the service using `npm start`.

## Local Setup

1. `npm install`
2. Create a `.env` file with `GEMINI_API_KEY=your_key`.
3. `npm start`