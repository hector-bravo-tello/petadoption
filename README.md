# Adopt a Pet!

Author: Hector Bravo

Welcome to "Adopt a Pet!", a React application designed to connect potential pet owners with adoptable pets. This project serves as a hands-on opportunity to practice implementing client-side routing using React Router. Gain experience in enhancing user navigation and interaction within a single-page application (SPA).

## Project Overview

"Adopt a Pet" allows users to browse and view detailed profiles of adoptable pets based on their species. It aims to create a seamless and intuitive experience for users looking to find their next furry friend. The application consists of several key components, including:

- **HomePage:** A component that fetches and displays all adoptable pets.
- **PetDetailsPage:** A component that shows detailed information for a specific pet.
- **SearchPage:** A page that allows users to search for pets by name.
- **PetNotFoundPage:** A page displayed when the details for a specific pet are not available.

## Objectives

Your main goal is to integrate client-side routing into the application using React Router with the following functionalities:

1. Dynamically display pets on the HomePage based on the species selected by the user.
2. Render the PetDetailsPage when a specific pet's ID is included in the browser's URL.
3. Ensure the PetDetailsPage shows information for the correct pet by leveraging URL parameters.
4. Redirect users to the SearchPage upon searching for a pet, using a query parameter to filter results.
5. Navigate to the PetNotFoundPage when details for a clicked pet are not available, with a "Go Home" button to return to the HomePage.

## Getting Started

Before diving into coding, familiarize yourself with the project structure, particularly the components located in the `src/` folder:

- `src/App.js` - The main App component.
- `src/pages/home/index.js` - The HomePage component.
- `src/pages/detail/index.js` - The PetDetailsPage component.
- `src/pages/search/index.js` - The SearchPage component.
- `src/pages/petNotFound/index.js` - The PetNotFoundPage component.

### Prerequisites

- Node.js installed on your system.
- Basic understanding of React and React Router.

### Setup

To get the project up and running on your local machine, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory and install the dependencies by running:

   ```
   npm install
   ```

3. Start the development server:

   ```
   npm start
   ```

   This will launch the application in your browser at `http://localhost:3000`.

### Mock Service Worker (MSW)

This project uses MSW to mimic the behavior of an external API. To ensure a smooth experience, use Google Chrome and enable third-party cookies.

## Contribution

Feel free to fork this repository and submit pull requests to contribute to the project. Whether it's adding new features, fixing bugs, or improving documentation, your contributions are welcome!

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
