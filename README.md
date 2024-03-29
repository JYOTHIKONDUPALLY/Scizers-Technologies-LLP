# Project Name: User Details

## Description
This project is a web application built using React.js and Material-UI that allows users to browse and view user details in a paginated format. The application features a search bar for filtering users, responsive user cards to display user details, and pagination functionality to navigate through the list of users.

**GitHub Link:** [Scizers Technologies LLP GitHub Repository](https://github.com/JYOTHIKONDUPALLY/Scizers-Technologies-LLP.git)

**Deployed Link:** [User Details Web Application](https://user-details-9ttr1ye3j-annem-jyothis-projects.vercel.app)

## Features
- **Search Bar:** Users can search for specific users by entering their names in the search bar. The application dynamically filters the user list based on the search query.
- **User Cards:** User details are displayed in a visually appealing card format. Each card includes information such as the user's name, gender, and other relevant details.
- **Pagination:** Pagination functionality is implemented to allow users to navigate through multiple pages of user data. Previous and Next buttons are provided for easy navigation.
- **Responsive Design:** The web application is responsive and adapts to different screen sizes, ensuring a seamless user experience across devices.

## Technologies Used
- **React.js:** Used as the primary JavaScript library for building the user interface and managing state.
- **Material-UI:** Leveraged for UI components and styling, providing a modern and consistent look and feel to the application.
- **Axios:** Utilized for making HTTP requests to fetch user data from an external API.

## Assignment Details
- **Company:** Scizers Technologies LLP
- **Job Role:** Internship

### Task
Fetch users from a public API and display using a React app. The API endpoint given below should be used for fetching data. The developer should also implement pagination, loader for fetching data, and error handling if the API server is down.

**API Endpoint:** https://swapi.dev/api/people

For each user, display a card with the following information:
- Name of the user
- A random picture of the user (random picture can be fetched from link https://picsum.photos/200/300)
- Hair color of the user
- Skin color of the user
- Gender of the user
- Count of vehicles the user has

The background color of the user's card must be the same as the hair color of the user.

There should be a search input to search for users by name. Users should enter a character name (partial or complete) and have all matching results returned.
