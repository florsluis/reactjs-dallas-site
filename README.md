# ReactJS Dallas on the web

Home of the ReactJS Dallas user group, founded in February 2016.

## How to Contribute 🤝

Whether you're helping us fix bugs, improve the docs, or spread the word, we'd love to have you as part of the ReactJS Dallas community! 😍

Check out the [contributor docs](/CONTRIBUTING.md) for ideas on contributing and setup steps for getting our repos up and running on your local machine.

**[Read the Contributing Guide](/CONTRIBUTING.md)**

### Code of Conduct

ReactJS Dallas is a safe place for anyone who wants to help build and develop any of our projects. We expect everyone participating in the ReactJS Dallas community to follow our [Code of Conduct](/CODE_OF_CONDUCT.md). Take a moment to read it. We have a long history of great experiences built on trust and learning all about React in a fun environment. Let's keep it going!

**[Read the Code of Conduct](/CODE_OF_CONDUCT.md)**

## Bootstrapped with...

The default Gatsby starter.

## Development Setup

1. Clone Repository: `git clone --depth=1 https://github.com/<your-username>/reactjs-dallas-site.git`
2. Setup up repo and install dependencies: `yarn`
3. Create a new firebase project
  1. Navigate to firebase.google.com
  2. Click 'Get Started'
  3. Click 'Add Project'
  4. Enter project information and click 'Create Project'
  5. In the project overview screen, click '</>' icon to get your API Key and other variables.
4. Create a .env file with the following variables (use the variables from your firebase project):
```
GATSBY_FIREBASE_API_KEY=
GATSBY_FIREBASE_AUTH_DOMAIN=
GATSBY_FIREBASE_DATABASE_URL=
GATSBY_FIREBASE_PROJECT_ID=
GATSBY_FIREBASE_STORAGE_BUCKET=
GATSBY_FIREBASE_MESSAGING_SENDER_ID=
```
5. Start the development project with `npm run develop`

## Live Site
https://www.reactjsdallas.com/

## License

This project is licensed under the terms of the
[MIT license](/LICENSE).
