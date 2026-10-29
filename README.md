# Repo Analyzer Demo

A simple, responsive website that analyzes **public GitHub repositories** and displays a quick overview of repository details, programming languages, and top-level files.

## Features

- Enter a public GitHub repository URL.
- View repository description, stars, forks, and last-updated time.
- See the detected programming languages and the main language.
- Browse a sample of files and folders at the repository root.
- View a basic project-type estimate based on repository files and languages.
- Responsive layout for desktop and mobile screens.

## Built With

- HTML
- CSS
- JavaScript
- GitHub REST API

## How to Run

1. Download or clone this project.
2. Open `repo-analyzer-demo.html` in a web browser.
3. Enter a public GitHub repository URL, for example:

   `https://github.com/microsoft/vscode`

4. Click **Analyze Repository**.

An internet connection is required because the page fetches repository information from GitHub's public API.

## Important Notes

- This demo works with **public repositories**. Private repositories are not supported.
- The file count shown is based on items at the repository root; it is not a count of every file in all nested folders.
- The project type is a simple estimate based on detected files and languages.
- GitHub may apply unauthenticated API rate limits. If a request is rate-limited, wait and try again later.
- Repository data can change over time.

## Project Structure

```text
repo-analyzer-demo/
└── repo-analyzer-demo.html
```

## Future Improvements

- Show recursive file counts for the full repository.
- Add charts for language breakdown.
- Display contributor information.
- Add loading, caching, and more detailed error states.
- Support authenticated access where appropriate, without exposing access tokens in client-side code.

## License

This project is provided for learning and demonstration purposes. Add a license file if you plan to distribute or reuse it publicly.
