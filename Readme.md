# Simple Jekyll + Tailwind CSS Starter Template

This is a simple starter template for creating a Jekyll site with Tailwind CSS. It includes basic setup and configuration for Jekyll, a static site generator, and Tailwind CSS, a utility-first CSS framework.

## Getting Started

Follow these steps to get your Jekyll + Tailwind CSS site up and running:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install tailwindcss @tailwindcss/typography cssnano postcss postcss-cli postcss-import autoprefixer` to install the necessary Node.js packages.
4. Run `bundle install` to install the necessary Ruby gems.
5. Run `bundle exec jekyll serve` to start the Jekyll server.

Your site should now be running at `http://localhost:4000`.

## Deploying to GitHub Pages

To deploy your site to GitHub Pages, follow these steps:

1. Open `_config.yml`.
2. Update `url: 'https://your-name.github.io'` with your GitHub Pages URL.
3. Update `baseurl: 'your-repo-name'` with the name of your GitHub repository.

Push your changes to GitHub, and your site should be live at `https://your-name.github.io/your-repo-name`.

## Credits

This template uses configurations and tweaks inspired by the following sources:

- [Use Jekyll and Tailwind CSS](https://medium.com/on-web-development/use-jekyll-and-tailwind-css-354ea2320e92)
- [Jekyllwind](https://github.com/mzrnsh/jekyllwind)
- [Starting a Blank Jekyll Site with Tailwind CSS in 2022](https://mzrn.sh/2022/04/09/starting-a-blank-jekyll-site-with-tailwind-css-in-2022/)
- [How to Use Tailwind CSS with Jekyll on GitHub Pages](https://mzrn.sh/2023/10/26/how-to-use-tailwind-css-with-jekyll-on-github-pages/)