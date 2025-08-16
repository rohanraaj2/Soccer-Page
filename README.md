
# Soccer-Page

Soccer-Page is a simple static website for sharing top soccer news and stories. It is built using HTML and CSS, and is hosted using Firebase Hosting.

## Features

- Responsive landing page with soccer news theme
- Navigation bar with links (Home, About, Blog, Contact)
- Eye-catching images and layout
- Section for new stories and articles
- Fixed footer with quick links

## Project Structure

```
Soccer-Page/
├── firebase.json           # Firebase Hosting configuration
├── .firebaserc             # Firebase project alias
├── public/
│   ├── index.html         # Main HTML file
│   └── style.css          # CSS styles
└── README.md              # Project documentation
```

## Deployment

This project uses [Firebase Hosting](https://firebase.google.com/docs/hosting) for deployment.

### To deploy your own version:

1. Install Firebase CLI if you haven't already:
   ```bash
   npm install -g firebase-tools
   ```
2. Log in to Firebase:
   ```bash
   firebase login
   ```
3. Initialize Firebase in your project directory (if not already done):
   ```bash
   firebase init
   ```
4. Deploy to Firebase Hosting:
   ```bash
   firebase deploy
   ```

## Live Demo

View the live site here: [https://soccer-page-eaa38.web.app/](https://soccer-page-eaa38.web.app/)
