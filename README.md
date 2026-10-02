# App Builder

A simple app for learning about robots.

## Current state
A mobile-first "Sign in with Google" login page (`index.html`) that redirects to a simple welcome page (`home.html`) with a sign-out button, an app list, a new-app form (`new-app.html`), and an app detail page with delete (`app.html`). No build step.

## Setup
1. In Google Cloud Console, create an OAuth 2.0 **Web application** client ID.
2. Add your page's origin (e.g. `http://localhost:8000`) to **Authorized JavaScript origins**.
3. Put the client ID in `GOOGLE_CLIENT_ID` in `index.html`.
4. Run `python3 -m http.server 8000` and open `http://localhost:8000`.
