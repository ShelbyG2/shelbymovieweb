# Shelby Movie Web

A launching point for building a movie streaming website.

## Features

- **Browse Movies**: Explore a vast collection of movies sorted by genre, release date, or popularity.
- **Search Functionality**: Easily find movies by title, director, or cast.
- **User Reviews**: Read and write reviews to share your thoughts and opinions about movies.
- **User Ratings**: Rate movies and see the average ratings provided by the community.
- **Recommendation Engine**: Get personalized movie recommendations based on your preferences and viewing history.
- **Responsive Design**: Enjoy a seamless experience across devices with our responsive web design.

## Deployments

### Deploy with Vercel

1. Click the "Deploy with Vercel" button below to start the deployment process:

- [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FShelbyG2%2Fshelbymovieweb&env=NEXT_PUBLIC_APP_URL,NEXT_PUBLIC_TMDB_TOKEN,NEXT_PUBLIC_SITE_NAME,NEXT_PUBLIC_TWITTER,NEXT_PUBLIC_INSTAGRAM)

2. If you haven't logged in to Vercel, you'll be prompted to do so. You can log in with your GitHub account.

3. Fill in the required environment variables:

   - `NEXT_PUBLIC_APP_URL`: Enter your deployment URL (e.g., `https://shelbymovieweb.vercel.app`)
   - `NEXT_PUBLIC_TMDB_TOKEN`: Your TMDb API key from [themoviedb.org](https://www.themoviedb.org/settings/api)
   - `NEXT_PUBLIC_SITE_NAME`: Your website name (e.g., `Shelby Movie Web`)
   - `NEXT_PUBLIC_TWITTER`: (Optional) Your Twitter handle
   - `NEXT_PUBLIC_INSTAGRAM`: (Optional) Your Instagram handle

4. Click "Deploy" and wait for the build process to complete.

5. Once deployed, Vercel will provide you with a URL where your site is live.

Note: You can always manage your deployment settings, environment variables, and domains from your Vercel dashboard.

### Deploy with Cloudflare Pages

To deploy on [Cloudflare Pages](https://pages.cloudflare.com/) you can use the following instructions:
[README](https://github.com/cloudflare/next-on-pages/tree/main/packages/next-on-pages)

## Local Development

1. Clone the repository: `git clone https://github.com/ShelbyG2/shelbymovieweb`
2. Navigate to the project directory: `cd movie-web-kickstart`
3. Install dependencies: `npm install`
4. Create .env file `cp .env.example .env`
5. Start the development server: `npm run dev`

## Tech Stack

- [Next.js](https://nextjs.org/) – framework
- [TypeScript](https://www.typescriptlang.org/) – language
- [Tailwind](https://tailwindcss.com/) – CSS
- [Vercel](https://vercel.com/) – deployments
- [TMDb](https://www.themoviedb.org/) - movie database
- [Vidsrc.cc](https://vidsrc.cc) - streaming links

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The Movie Database (TMDb) for providing the movie data through their API.
- [Vidsrc.cc](https://vidsrc.cc) for providing the movie streaming links.

---
