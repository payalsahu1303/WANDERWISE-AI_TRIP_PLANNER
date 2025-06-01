# Wander Wise - AI Trip Planner
An AI-powered trip planner that simplifies travel planning. With **Wander Wise**, users can sign in, provide trip preferences, and receive AI-curated itineraries, including top-rated hotels and day-wise plans. 

![Screenshot 2024-11-22 204310](https://github.com/user-attachments/assets/d2228d9d-3d77-46de-8f60-d19b3cf546a7)


## Technologies Used  
### Frontend  
- **React + Vite**: For a fast and modern development experience.  
- **Tailwind CSS**: To create a sleek, responsive UI with minimal effort.  
- **ShadCN UI**: Leveraging components like buttons, inputs, popovers for a polished user experience.  

### APIs  
- **Gemini AI API**: For generating AI-curated itineraries based on trip details.  
- **Google Cloud Platform**:  
  - **Places API**: Fetching details of destinations.  
  - **Geocoding API**: Translating addresses into geographic coordinates.  
  - **Geolocation API**: Determining user locations for better personalization.  
  - **Place API (New)**: Providing enriched location details for travel recommendations.  

### Authentication & Database  
- **Firebase**:  
  - **Authentication**: Enables secure Google-based sign-in.  
  - **Cloud Firestore**: For storing user profiles, trip details, and itineraries.  

### Libraries  
- **React Google Places Autocomplete**: Autocomplete suggestions for destination input.  
- **React OAuth2 Google**: Google authentication integration.  

---

## Features  
### 1. **Header**  
- Includes a **Sign-In Button** for users to log in with Google.  
- After logging in, the user's **profile picture and email** are displayed dynamically.  

### 2. **Home Page**  
- **Hero Section**: Engaging banner that introduces the app's purpose.  
- **About Section**: Overview of the features and the power of AI in trip planning.  
- **Gallery Section**: Showcases curated travel photos fetched using **Google Cloud Place API**.  
- **Footer**: Contains social media links, contact details, and app credits.  

### 3. **Trip Planning Page**  
- Form fields:  
  - **Destination**: Autocomplete suggestions using **Google Places API**.  
  - **Duration**: Number of days for the trip.  
  - **Budget**: Estimated budget for the trip.  
  - **Number of Travelers**: Helps AI customize the itinerary.  
- AI curates:  
  - **Day-Wise Itinerary**: Activities and plans for each day of the trip.  
  - **Top-Rated Hotels**: Suggestions with images, ratings, and location fetched using **Google APIs**.  

### 4. **View Trip Page**  
- Displays the AI-generated itinerary with:  
  - **Hotels Section**: Highlights the best accommodations with details.  
  - **Itinerary Section**: Day-by-day breakdown of planned activities.  
- Dynamic and responsive UI ensures a seamless user experience.  
