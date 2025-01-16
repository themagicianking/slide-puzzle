# Slide Puzzle

![javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![express](https://img.shields.io/badge/Express%20js-000000?style=for-the-badge&logo=express&logoColor=white) ![vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E) ![unsplash](https://img.shields.io/badge/Unsplash-000000?style=for-the-badge&logo=Unsplash&logoColor=white)

This is a slide puzzle game initially created for a Techtonica assignment. I am still working on basic functionality so the game can actually be played; currently, the app shuffles a random image into pieces but there is no user ability to move those pieces around.

## Installation

1. Clone the repository to your local machine.
2. Create a developer account at [Unsplash](https://unsplash.com/) and follow their instructions to get your own API key.
3. Remove the "example" part of the example.env file and paste in your API key (note: this is labeled as the access key in the developer dashboard, not the secret key).
4. Navigate to the server directory and run `npm install`, then run `npm run start`.
5. Navigate to the client directory and run `npm install` again, then `npm run dev`.
6. Open the port that the terminal window displays when you run the client and open it in your browser.

## Usage

The user may select a category for their puzzle and a random image will be displayed based on the category selected when the user clicks "get puzzle". The "shuffle puzzle" button will mix pieces of the image into smaller 4 by 4 images.

## Components

- Puzzle
- RandomImage
- ShufflePuzzle
- Tile

## Testing

This project currently does not have any testing.

## To Do

- [ ] Chain server start to client start so only one command is needed to get both running
- [ ] Double check that setup instructions will install all dependencies correctly
- [ ] Add ability to move tiles with arrow keys
- [ ] Add ability to move tiles by clicking with mouse
- [ ] Add win screen if user solves the puzzle with "play again" button
- [ ] Add testing

## Reference

- This project uses [Unsplash's API](https://unsplash.com/developers) server side to fetch both images and image descriptions.