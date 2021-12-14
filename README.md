<h1 align="center">
  ig.news
</h1>

<p align="center">
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-requirements">Requirements</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<p align="center">
  <img  src="https://img.shields.io/github/license/murilorvargas/ig-news?color=EBA417&labelColor=61DAFB" alt="License">
  
  <img src="https://img.shields.io/github/languages/top/murilorvargas/ig-news?color=EBA417&labelColor=61DAFB" alt="Languages">

  <img src="https://img.shields.io/github/repo-size/murilorvargas/ig-news?color=EBA417&labelColor=61DAFB" alt="Stars">
</p>

<br>

<p align="center">
  <img alt="ig-news" src="src/assets/github/ig-news.png" width="100%">
</p>

## 🚀 Technologies

The following tools were used in this project:

- [ReactJS](https://reactjs.org/)
- [NextJS](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [SASS](https://sass-lang.com/)
- [Next-Auth](https://next-auth.js.org/)
- [Stripe](https://stripe.com/)
- [FaunaDB](https://fauna.com/)
- [Prismic CMS](https://prismic.io/)

## 💻 Project

Ig.news is an application that provides paid content about React.js. The user registers, makes a monthly payment and has access to the application's posts.

Ignews was developed in React.js with Next.js, TypeScript and Sass, the application authentication is done by the user's GitHub account. Subscription and payment for viewing content is handled by Stripe. Posts are managed through CMS Prismic and subscription data is stored in Faunadb.

## ✅ Requirements

Required to install:

- [Git](https://git-scm.com/)
- [Yarn](https://classic.yarnpkg.com)
- [Stripe CLI](https://stripe.com/docs/stripe-cli)

Create account and configure external services:

- [Stripe](https://stripe.com/)
- [FaunaDB](https://fauna.com/)
- [Prismic CMS](https://prismic.io/)

## 🏁 Starting

```bash
# Clone this project
$ git clone https://github.com/murilorvargas/ig-news
# Access
$ cd ig-news
# Install dependencies
$ yarn

# Create an .env.local file and place environment variables based on the .env.example file

# Run stripe listen to listen for webhook events
$ stripe listen --forward-to localhost:3000/api/webhooks
```

Now run on another terminal:

```bash
# Run the project
$ yarn dev
# The server will initialize in the <http://localhost:3000>
```

## :memo: License

This project is under license from MIT. For more details, see the [LICENSE](LICENSE) file.