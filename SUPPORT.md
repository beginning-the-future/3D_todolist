# 3D_todolist 🌌

A futuristic, J.A.R.V.I.S.-inspired 3D to-do list built around a
galaxy-themed interface. Organize tasks into lists, manage priorities
and deadlines, and sign in to access your personal task space.

## Features

-   **Galaxy-inspired interface** with a futuristic J.A.R.V.I.S.
    aesthetic
-   **Task and list management** to create, organize, rename, and remove
    lists and tasks
-   **Task details** including priority, deadline, repeat options, and
    notes
-   **3D / 2D views** for different ways to explore your tasks
-   **Firebase Authentication** for supported sign-in options, including
    username/password and Google
-   **Guest access** using Firebase anonymous authentication, when
    enabled and configured
-   **Cloud data storage** through Cloud Firestore, when configured
-   **Import and export** support for task data where available in the
    app

## Built With

-   HTML, CSS, and JavaScript
-   Firebase Authentication
-   Cloud Firestore
-   GitHub Pages for static hosting (optional)

## Getting Started

1.  Clone or download this repository.
2.  Open the HTML file locally, or run it with a local development
    server such as VS Code Live Server.
3.  To use authentication and cloud sync, create a Firebase project and
    register a web app.
4.  Add your Firebase web app configuration to the configuration object
    in the HTML file.
5.  Enable the sign-in providers you use in **Firebase Console →
    Authentication**.
6.  Create a Cloud Firestore database and publish appropriate security
    rules.
7.  Add your development or deployment domain to Firebase
    Authentication's **Authorized domains**.

> Firebase authentication and cloud sync will not work until the
> Firebase project, authorized domains, and Firestore rules are
> configured correctly.

## Deploy with GitHub Pages

1.  Ensure the main page is named `index.html` and is in the repository
    root, or adjust the Pages configuration to match your file.
2.  Push your changes to GitHub.
3.  Open **Settings → Pages** in the repository.
4.  Select **Deploy from a branch**, then choose your branch and root
    folder.
5.  Add the published hostname to Firebase Authentication's authorized
    domains.
6.  Test sign-in and confirm each account can access only its own data.

## Security Notes

-   Never put Firebase Admin SDK credentials, service-account private
    keys, or other server secrets in the HTML or repository.
-   Firebase web configuration is client-side configuration; access to
    Firestore data must be protected by Firestore Security Rules.
-   Test with separate accounts before sharing the site publicly.
-   Anonymous accounts are temporary identities unless users link them
    to a permanent sign-in method. Provide a linking/recovery flow if
    you want guest progress to persist across identity changes.

## Project Status


## 📬 Support & Feedback

Have a question, found a bug, or have an idea to improve J.A.R.V.I.S.?

- **Bug reports:** [Report an issue](https://github.com/beginning-the-future/3D_todolist/issues)
- **Feature requests:** Open an issue with the `enhancement` label.
- **Email support:** beginningthefuture21@gmail.com

Your feedback helps improve the J.A.R.V.I.S. Galaxy Task System! 🌌


A personal web project under development. Firebase features depend on
the project's current configuration and security rules.

------------------------------------------------------------------------

Built with ☄️ and a little Stark-level ambition.
