# Weather App with Blog Integration

A modern React application that combines weather information, blog posts, and a developer profile section.

## Features

- Real-time weather information using OpenWeatherMap API
- Latest blog posts from sudipsharma.com.np
- Google AdSense integration
- Developer profile section
- Responsive design with Tailwind CSS

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Copy `.env.example` to `.env` and update the environment variables:
   ```bash
   cp .env.example .env
   ```
   Then update the following variables in `.env`:
   - `REACT_APP_WEATHER_API_KEY`: Your OpenWeatherMap API key
   - `REACT_APP_ADSENSE_CLIENT_ID`: Your Google AdSense client ID
   - `REACT_APP_ADSENSE_SLOT_ID`: Your Google AdSense slot ID

4. Start the development server:
   ```bash
   npm start
   ```

## Deployment to Netlify

1. Push your code to a GitHub repository

2. Connect to Netlify:
   - Sign in to Netlify
   - Click "New site from Git"
   - Choose your repository
   - Set build command: `npm run build`
   - Set publish directory: `build`

3. Configure environment variables:
   - Go to Site settings > Build & deploy > Environment
   - Add the following environment variables:
     - `REACT_APP_WEATHER_API_KEY`
     - `REACT_APP_ADSENSE_CLIENT_ID`
     - `REACT_APP_ADSENSE_SLOT_ID`

4. Deploy:
   - Netlify will automatically deploy your site
   - Any future pushes to the main branch will trigger automatic deployments

## Built With

- React
- Tailwind CSS
- OpenWeatherMap API
- RSS2JSON API
- Google AdSense

## Author

Sudip Sharma
- Website: [sudipsharma.info.np](https://sudipsharma.info.np)
- GitHub: [@sudipsharma826](https://github.com/sudipsharma826)
- LinkedIn: [sudipsharmanp](https://www.linkedin.com/in/sudipsharmanp)
#   W e a t h e r - A p p  
 