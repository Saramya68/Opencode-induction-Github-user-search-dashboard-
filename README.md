**GitHub User Search Dashboard

Deployed website:https://saramya68.github.io/Opencode-induction-Github-user-search-dashboard-/ 

A responsive web dashboard that allows users to search for GitHub profiles using the GitHub Public Search API.
The app includes real-time search with debounce, pagination, loading/error states, and localStorage caching for a better user experience.


**Features

1.Search GitHub Users by username
2.Loading & Error States for better feedback
3.Pagination (Next / Previous)
4.Debounced Search to reduce unnecessary API calls
5.LocalStorage Caching (restores last search & page)
6.Responsive UI using CSS Grid
7.Clean, modern UI inspired by GitHub Dark Theme
8.Tech Stack
9.HTML5
10.CSS3
11.Vanilla JavaScript


**GitHub Search API

📂 Project Structure
📁 github-user-dashboard
│── index.html
│── git.css
│── git.js
│── README.md


**How It Works (Brief)

=>Users type in the search box
=>Input is debounced (600ms) before triggering API call
=>GitHub API fetches users with pagination support
=>Results are displayed as cards
=>Search query & page number are saved in localStorage
=>On reload, the app restores the last search automatically


**API Used

GitHub Search Users API
https://api.github.com/search/users


**Notes
GitHub API has rate limits for unauthenticated requests
Debounce helps prevent hitting the limit too quickly
Best viewed on modern browsers (Chrome, Edge, Firefox)
