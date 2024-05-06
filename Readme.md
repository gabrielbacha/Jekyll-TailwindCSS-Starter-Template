# Simple Jekyll + Tailwind CSS Starter Template

This is a simple starter template for creating a Jekyll site with Tailwind CSS. It includes basic setup and configuration for Jekyll, a static site generator, and Tailwind CSS, a utility-first CSS framework.

## Getting Started

Follow these steps to get your Jekyll + Tailwind CSS site up and running:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install tailwindcss @tailwindcss/typography cssnano postcss postcss-cli daisyui postcss-import autoprefixer` to install the necessary Node.js packages.
4. Run `bundle update` to update the Ruby dependencies.
5. Run `bundle install` to install the necessary Ruby gems.
6. Run `bundle exec jekyll serve -l -o` to start the Jekyll server.

Your site should now be running at `http://localhost:4000`.

## Deploying to GitHub Pages

To deploy your site to GitHub Pages, follow these steps:

1. Open `_config.yml`.
2. Update `url: 'https://your-name.github.io'` with your GitHub Pages URL.
3. Update `baseurl: 'your-repo-name'` with the name of your GitHub repository.
4. Run `bundle lock --add-platform x86_64-linux` to add the Linux platform to the Gemfile.lock.
5. Run `bundle lock --add-platform ruby` to add the Ruby platform to the Gemfile.lock.
6. Push the changes to your GitHub repository.
7. After the GitHub Actions workflow runs successfully, go to the GitHub Pages settings and deploy from the `gh-pages` branch.


Your site should be live at `https://your-name.github.io/your-repo-name`.

## Credits

This template uses configurations and tweaks inspired by the following sources:

- [Use Jekyll and Tailwind CSS](https://medium.com/on-web-development/use-jekyll-and-tailwind-css-354ea2320e92)
- [Jekyllwind](https://github.com/mzrnsh/jekyllwind)
- [Starting a Blank Jekyll Site with Tailwind CSS in 2022](https://mzrn.sh/2022/04/09/starting-a-blank-jekyll-site-with-tailwind-css-in-2022/)
- [How to Use Tailwind CSS with Jekyll on GitHub Pages](https://mzrn.sh/2023/10/26/how-to-use-tailwind-css-with-jekyll-on-github-pages/)
- [First deployment with GITHUB_TOKEN](https://github.com/peaceiris/actions-gh-pages?tab=readme-ov-file#%EF%B8%8F-first-deployment-with-github_token)