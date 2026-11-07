# JessyGist Publisher Android App

This Android wrapper opens the existing JessyGist Admin dashboard inside an app window.

## What it does
- Opens the existing Admin.html dashboard.
- Supports Firebase email/password sign-in through the website.
- Supports selecting an image from the phone for the existing Cloudinary upload form.
- Uses the existing Firestore database and security rules.

## Important
The app does not store Firebase passwords or Cloudinary secrets. Sign in through the existing secure Firebase login page. Firestore rules remain the authority for protecting article data.

The app requires an internet connection. The dashboard is hosted at:
https://jessygisting.github.io/JessyGist/Admin.html
