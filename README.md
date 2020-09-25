# Gihub-Finder React Application

## Overview

GitHub Finder is a React application that was built merely for the personal exposure of the different
development approaches available within React. HTTP requests made to the GitHub REST API via Axios returns
GitHub profile results based on user input within the search bar. Information is then displayed for the selected
profiles, along with links to the five latest repositories for that user.
This application started off implementing class base components
and stateless functional components.
After achieving the desired functionality of the application, the code was refactored into all-functional
components using hooks, such as useState and useEffect. Finally, the code was refactored once again implementing
app-level state using the Context API, the useReducer hook, and the useContext hook. The application has been
deployed via Netlify.

### Technologies in Use

- [React](https://reactjs.org/)
- [GitHub REST API](https://docs.github.com/en/rest) for deployment
- [Axios](https://www.npmjs.com/package/axios)
- [Netlify](https://www.netlify.com/) for deployment

### See it work:

[GitHub-Finder](https://githubfinder86753090210.netlify.app/)
