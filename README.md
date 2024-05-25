## Project overview

_Title:_ Medify

_Description:_ A web application designed to help users find the nearest hospitals by selecting their state and city. The app allows users to book appointments at hospitals and check their appointments after booking. It's targeted towards individuals seeking convenient access to healthcare facilities.

_Live URL:_ https://medify-three.vercel.app/

## Role and Responsibilities

I was the sole developer of this project, responsible for the entire front-end development using React. The design was provided to me, and I managed everything from translating the design into a functional interface to implementing and integrating APIs for fetching cities and managing bookings.

## Technical Stack

- _React:_ React was chosen for its component-based architecture, which facilitates reusability and efficient UI development. Its virtual DOM ensures high performance, and its large ecosystem provides robust tools and community support.
- _MUI (Material-UI):_ It has rich set of pre-designed components following Google's Material Design guidelines. This allows for rapid development of a polished user interface with consistent styling.
- _Axios:_ Axios was used for making HTTP requests due to its simplicity and promise-based architecture, which makes it easier to handle asynchronous operations compared to native fetch API. It also offers robust features like request and response interceptors.
- _date-fns:_ date-fns was chosen for date manipulation and formatting because of its lightweight nature and functional programming approach. It provides a rich set of functions without the overhead of larger libraries like Moment.js.
- _Swiper:_ Swiper was implemented for creating touch sliders and carousels due to its responsiveness and extensive customization options. It enhances the user experience by enabling smooth and interactive navigation elements.

## Key Features and Functionality

- Dynamic search functionality where users can select their state and then fetch corresponding cities via an API.
- Users can then see a list of nearby hospitals and book an appointment directly through the website.
- After booking, users can log in to check their appointment details.
- The interface is designed to be user-friendly and responsive across different devices.
