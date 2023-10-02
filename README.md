
# Movie Search App Tutorial

![moviepic2](https://github.com/ubcodes/movie_search_site_tutorial/assets/101749091/b54042e1-8be8-45c9-9dee-3f47ddec671b)


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Movie Search App is a React-based web application that allows users to search for  movies. It uses the [OMDb API](https://www.omdbapi.com/) to fetch movie data, providing details such as movie titles, type, posters, and release dates. This site is designed to help movie enthusiasts discover new films and access information about their favorite movies.

## Features

- Search for movies by title.
- Responsive design for mobile and desktop devices.
- User-friendly interface for an intuitive movie search experience.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm (Node Package Manager) installed on your local machine.
- API Key from [OMDb](https://www.omdbapi.com/) (The Movie Database) to access movie data. (Note: This is required as the app uses OMDb API for fetching movie information).

## Installation

To get the Movie Search App up and running on your local machine, follow these steps:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/ubcodes/movie_search_site_tutorial.git
   ```

2. Navigate to the project directory:

   ```shell
   cd movie-search-app
   ```

3. Install the project dependencies:

   ```shell
   npm install
   ```

4. Create a `.env` file in the root directory of the project and add your TMDb API key:

   ```shell
   REACT_APP_TMDB_API_KEY=your-api-key-here
   ```

5. Start the development server:

   ```shell
   npm start
   ```

6. Open your web browser and visit `http://localhost:3000` to use the Movie Search App.

## Usage

1. Enter a movie title in the search bar and press "Search."

2. Browse through the search results to find the movie you are looking for.

3. Click on a movie card to view detailed information about that movie.

4. Explore movie details, including the title, description, release date, and user ratings.

5. Enjoy discovering new movies and accessing information about your favorites!

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.

2. Clone your forked repository to your local machine.

3. Create a new branch for your feature or bug fix:

   ```shell
   git checkout -b feature/your-feature-name
   ```

4. Make your changes and commit them:

   ```shell
   git commit -m "Add your commit message here"
   ```

5. Push your changes to your GitHub repository:

   ```shell
   git push origin feature/your-feature-name
   ```

6. Create a Pull Request on GitHub, describing your changes and their purpose.

7. Wait for a maintainer to review your Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

