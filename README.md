# Hacker Times - Hacker News as a newspaper front page

Hacker Times is a single-page web app that shows the top stories from
[Hacker News](https://news.ycombinator.com) laid out like a newspaper front page.
The most upvoted story gets the biggest headline.

Read it [here](https://etnt.github.io/hacker-times/)

## Features

- **Newspaper layout:** masthead, lead story banner, secondary headlines, columns, and a sidebar.
- **Teasers:** the first paragraph of each story (up to 200 characters).
- **Photos:** screenshots of the top 3 linked articles.
- **Comments:** open a story's comments in a modal.
- **Info box:** front-page stats, top linked domains, and the most-starred GitHub repositories from the last week.

## Running it

Open `index.html` in a browser. An internet connection is required.

No build step or install is needed.

## Data sources

- Hacker News API (`hacker-news.firebaseio.com`): stories and comments.
- [Jina Reader](https://r.jina.ai): article text for teasers on linked stories.
- [thum.io](https://image.thum.io): screenshots for the top 3 linked articles.
- GitHub Search API: most-starred repositories this week.

The Jina Reader and thum.io services are third parties. Their limits and terms apply.

## Deployment

A GitHub Actions workflow (`.github/workflows/deploy-pages.yml`) publishes
`index.html` to GitHub Pages on every push to `main`.

## License

This project is licensed under the Mozilla Public License 2.0 (MPL-2.0).
See [LICENSE](LICENSE) for the full text.
