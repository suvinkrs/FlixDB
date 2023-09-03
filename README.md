# Movie Details Website

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

The Movie Details Website is a React-based web application that allows users to fetch details of popular movies from the TMDb (The Movie Database) API. This project provides a user-friendly platform for movie enthusiasts to explore information about their favorite films. It features a landing page showcasing popular movies and a dedicated movie detail page that offers in-depth information about individual movies. The website leverages a component library consisting of a card component for movie display, a header component for navigation, and a movie list component for rendering lists of movies.

## Features

- **Popular Movies Display**: The landing page displays a list of popular movies retrieved from the TMDb API, allowing users to browse through them.
- **Movie Detail Page**: Users can click on a movie card to access a dedicated movie detail page containing comprehensive information about the selected movie.
- **Component Library**: The project includes a component library that provides reusable components for consistent UI design:
  - **Card Component**: Used for displaying movie information on the landing page and in the movie detail page.
  - **Header Component**: Provides navigation to switch between the landing page and the movie detail page.
  - **Movie List Component**: Renders lists of movies with options for sorting and filtering.

## Technologies Used

- **React**: Building the user interface and managing state efficiently.
- **React Router**: Handling navigation and creating multiple pages within the single-page application.
- **Component Library**: Reusable components (Card, Header, Movie List) for consistent UI design.
- **TMDb API**: Fetching movie data from the TMDb database.

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

2. Install the project dependencies:

```bash
npm install
```

3. Set up API Key:

   - Visit the [TMDb API](https://www.themoviedb.org/documentation/api) website and sign up for an API key.
   - Create a `.env.local` file in the project root directory.
   - Add your TMDb API key to the `.env.local` file as follows:

   ```env
   REACT_APP_TMDB_API_KEY=your-tmdb-api-key
   ```

4. Start the development server:

```bash
npm start
```

5. Open your web browser and navigate to `http://localhost:3000` to access the website.

## Usage

- On the landing page, explore a list of popular movies.
- Click on a movie card to access the movie detail page.
- On the movie detail page, view comprehensive information about the selected movie.
- Navigate between the landing page and movie detail page using the header.

## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add feature XYZ'`.
4. Push your changes to your fork: `git push origin feature-name`.
5. Open a pull request against the main repository.

## License

This project is licensed under the [MIT License](LICENSE).
