# GitHub User Fetcher

## Summary
This application fetches a GitHub user's account creation date using their username and displays the account age.

## Setup
1. Clone the repository.
2. Open `index.html` in your web browser.

## Usage
1. Enter a GitHub username in the input field.
2. Click the 'Fetch User' button to retrieve the account creation date and age.

## Code Explanation
- The form with id `github-user-12345` captures the username input.
- On form submission, the `fetchUser` function is called, which makes a request to the GitHub API.
- An aria-live alert with id `github-status` reports the status of the lookup.
- The account creation date and age in years are displayed in the `#github-account-age` element.
- The last successful lookup is cached in localStorage to repopulate the form on load.

## License
This project is licensed under the MIT License.