# Github repository for SFMO's webpage.

Welcome to the repository for your SFMO's webpage using [GitHub Pages](https://pages.github.com). This project uses [Jekyll's Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme for rendering the UI components.

# Getting Started

The visible pages' contents are mostly written in Markdown thus they are also easily modifiable. Good cheat sheet for Markdown syntax can be found from [here](https://www.markdownguide.org/cheat-sheet/).

## Changing page contents (for quick modifications):
 1. Find the page that you want to modify from the [main branch](https://github.com/SFMO-ry/sfmo-fi). The pages are mostly found in _pages folders and are in .md files.
 2. Open the file in GitHub, and click on the edit button to modify the content.
![image](https://github.com/SFMO-ry/sfmo-fi/assets/63156337/c80f9da2-dea0-4e65-9e78-05ebd69cd4dc)
 3. After finishing the modifications, click on Commit changes... on top right, write a commit message and description on what has been done and commit the changes. Now the GitHub actions should start automatically deploying the changes.
 4. Check on the [Github Actions page](https://github.com/SFMO-ry/sfmo-fi/actions) that the modifications have went through without issues.
 5. Now the text should be updated on the webpage.


## Setup for local development:
### Prerequisites
Instructions on installing Ruby and Jekyll for Windows can be found [here](https://jekyllrb.com/docs/installation/windows/). 
- [Ruby](https://www.ruby-lang.org/)
- [Bundler](https://bundler.io/)

1. Fork this repository by clicking on the "Fork" button at the top right of this page. This creates a copy of the repository in your GitHub account.
2. Clone your forked repository to your local machine. Replace `your-username` with your GitHub username and `your-repo` with the name of your forked repository.
   ```bash
   # Clone your forked repository
   git clone https://github.com/your-username/your-repo.git
4. Install dependencies:
   ```bash
    bundle install
6. Run the Jekyll server:
   ```bash
    bundle exec jekyll server
7. If you want to see your changes on local <user>.github.io page, follow the instructions here: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site.
