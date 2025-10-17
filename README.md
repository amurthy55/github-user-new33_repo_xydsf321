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
- On form submission, the `fetchUser` function is called to perform the lookup.
- The account creation date and age are displayed in the designated areas.
- The app provides aria-live updates for status messages during the lookup process.
- The last successful lookup is cached in localStorage for user convenience.

## License
This project is licensed under the MIT License.