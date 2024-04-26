# GeekPeek

GeekPeek is a React.js project that allows users to search for movies and play their trailers. It utilizes The Movie Database (TMDb) API to fetch movie data and trailers. With GeekPeek, you can easily find information about your favorite movies and watch their trailers without leaving the application.

## Features

- **Movie Search**: Search for movies by title, keyword, or any other relevant information. Get detailed information about the movies, including the title, release date, overview, and poster.

- **Movie Trailers**: Watch trailers of the selected movies. GeekPeek provides an embedded video player for a seamless viewing experience.

## Getting Started

To run GeekPeek on your local machine, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/AnshumanGiramkar/GeekPeek-ReactJs.git
   ```

2. Navigate to the project directory:

   ```
   cd geekpeek
   ```

3. Install the required dependencies:

   ```
   npm install
   ```

4. Obtain an API key from The Movie Database (TMDb) by following their [API documentation](https://developers.themoviedb.org/3/getting-started/introduction).

5. Create a `.env` file in the project root and add your TMDb API key:

   ```
   REACT_APP_TMDB_API_KEY=your-api-key
   ```

6. Start the development server:

   ```
   npm start
   ```

7. Open your web browser and access `http://localhost:3000` to use GeekPeek.

## Usage

1. In the search bar at the top, enter the title or keyword related to the movie you want to search for.

2. Click the "Search" button or press Enter to initiate the search.

3. The search results will be displayed below, showing movie posters and titles. Click on a movie to see more details.

4. To watch the movie's trailer, click the "Play Trailer" button. The trailer will be displayed in an embedded video player.

## Technologies Used

- React.js: Front-end framework for building the user interface.
- The Movie Database (TMDb) API: For fetching movie data and trailers.
- Axios: For making API requests.
- Embed API: For embedding YouTube trailers.

## Project Structure

- `src/`: Contains the source code for the GeekPeek project.
  - `components/`: React components used to build the application.
  - `App.js`: The main application component.
  - `index.js`: Entry point for the application.

## Troubleshooting

If you encounter any issues while running GeekPeek, please make sure you have:

- Installed the necessary dependencies using `npm install`.
- Set up your TMDb API key in the `.env` file.
- Enabled CORS (Cross-Origin Resource Sharing) in your browser, as the application makes API requests.

## License

This project is open-source.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to help improve GeekPeek.

## Author

Anshuman Giramkar

## Acknowledgments

GeekPeek was created with the help of various online tutorials, resources, and the support of the open-source community. A big thank you to everyone who contributed to the development of this project.

---

Happy movie searching and trailer watching with GeekPeek! 🎬🍿
