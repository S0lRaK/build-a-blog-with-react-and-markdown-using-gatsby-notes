# [01. Install the Latest Version of Gatsby](https://egghead.io/lessons/gatsby-install-the-latest-version-of-gatsby)


## Course repo

## ⚠️ Dealing with Deprecation

The `v2` branch is no longer present on the `gatsbyjs/gatsby-starter-hello-world` instead use:

```bash
gatsby new my-blog https://github.com/gatsbyjs/gatsby-starter-hello-world
```

> An alternative, and recommended way to successfully follow the course:

```bash
gatsby new git@github.com:eggheadio-projects/build-a-blog-with-react-and-markdown-using-gatsby-code.git
```

Install dependencies:

```bash
npm install
```

Change directories into site folder and start development server.

```bash
cd build-a-blog-with-react-and-markdown-using-gatsby-code
```

```bash
gatsby develop
```

Gatsby will start a hot-reloading development environment accessible by default at http://localhost:8000.

## Start development server

Try editing the JavaScript pages in `src/pages`. Saved changes will live reload in the browser.
