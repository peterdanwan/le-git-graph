<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://drive.google.com/uc?export=download&id=1brZLKMazyQXd7jznNX-sPfKsZ9uUfJTh">
  <source media="(prefers-color-scheme: light)" srcset="https://drive.google.com/uc?export=download&id=1OqQqmJdKCEJzxz8rDo7OhnAxVyNYl1eA">
  <img alt="Github Tree Graph" src="https://drive.google.com/uc?export=download&id=1OqQqmJdKCEJzxz8rDo7OhnAxVyNYl1eA">
</picture>


A browser extension that displays the git graph for any GitHub repository.

[![Status](https://img.shields.io/badge/Status-Beta-yellowgreen)]()
[![Manifest](https://img.shields.io/badge/Manifest-V3-green)]()
[![Version](https://img.shields.io/badge/Version-0.0.0.1-yellowgreen)]()

## Demo
![Demo image](https://drive.google.com/uc?export=download&id=12plJnQgqAvSecLz5jrLajojtuRX2aPyZ)


## Installation

Install the extension from Chrome Web store

[https://chrome.google.com/webstore/detail/github-tree-graph/joggkdfebigddmaagckekihhfncdobff](https://chrome.google.com/webstore/detail/github-tree-graph/joggkdfebigddmaagckekihhfncdobff)


After installation, open any GitHub repository and a new 'Commits' tab will be visible.

Open the commits tab and follow the prompt to authenticate with your GitHub account.
## Tech Stack

**Client:** JavaScript, Manifest V3

**Server:** GitHub GraphQL, GitHub OAuth, FireBase Cloud Functions


## Features

- Authentication with GitHub OAuth  ✓
- Migrate OAuth backend from Heroku to Firebase Functions - Pending
- Connection to GitHub GraphQL ✓
- Fetch the commits data from API ✓
- Fetch further commits on demand ✓
- Filter the commits based on branch - Pending
- Upload to chrome webstore - ✓

## Contact

Feel free to drop a mail at scaria@scaria.dev or nirmalscaria1@gmail.com
