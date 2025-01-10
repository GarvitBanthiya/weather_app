# **Weather App**

A responsive weather application built using **HTML**, **CSS**, and **JavaScript**, which allows users to view weather information based on their current location or search for a specific city.

---

## **Features**

- **Get Weather by Location**:  
  Users can grant location access to display weather information for their current location.  
   
- **Search Weather by City**:  
  Users can search for weather information by entering the city name in the search bar.

- **Loading Indicator**:  
  A loading screen is displayed while the weather data is being fetched.

- **Error Handling**:  
  If an invalid city is entered or location services are unavailable, an error message is displayed.

- **Responsive Design**:  
  The app is fully responsive and works on various screen sizes, including mobile, tablet, and desktop.

---

## **Technologies Used**

- **HTML5**: Markup structure for the app.  
- **CSS3**: Styling and responsive layout using media queries.  
- **JavaScript**: Core functionality including API calls, DOM manipulation, and error handling.  
- **OpenWeather API**: Used to fetch real-time weather data.  

---

## **API Key Setup**

The project uses the **OpenWeather API** to fetch weather data. Follow these steps to set up your API key:

1. Go to [OpenWeather](https://openweathermap.org/) and create an account.  
2. Generate an API key from the dashboard.  
3. Replace the placeholder API key in the `index.js` file with your own:
   ```javascript
   const API_KEY = "your_api_key_here";
   ```

---

## **Media Queries**

The app includes media queries to ensure it works on different devices:

- **Mobile**: Layout is optimized for smaller screens.  
- **Tablet**: Elements are adjusted for medium-sized screens.  
- **Desktop**: Full layout with maximum width and proper spacing.

---

## **Screenshots**
![Screenshot 2025-01-10 224525](https://github.com/user-attachments/assets/fa8e60a0-b20a-4f86-8f2a-78290003fbf8)

![Screenshot 2025-01-10 224551](https://github.com/user-attachments/assets/4d12fae9-a551-44a1-ab8b-8eb975bc6158)

![Screenshot 2025-01-10 224647](https://github.com/user-attachments/assets/4c8fc796-031b-4b57-9115-a285a3d12597)

