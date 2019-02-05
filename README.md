# New Post Scaffold for Gatsby Starter Blog

> A cli tool to create a new post and frontmatter for Gatsby Starter Blog

[Joel Hooks](https://twitter.com/jhooks), creator of [egghead.io](https://egghead.io) [wrote a post](https://joelhooks.com/a-handy-npm-script-for-creating-a-new-gatsby-blog-post) on automating new posts for Gatsby with a basic npm script.

My script is basically his, with minor modifications; I'm using markdown here and the frontmatter format for this script is *specifically* for [Gatsby Starter Blog](https://www.gatsbyjs.org/starters/gatsbyjs/gatsby-starter-blog/). For an idea of how that starter is setup, checkout my [TWBlog repo's src directory](https://github.com/twhite96/TWBlog/src/pages).

## Usage

Open your terminal of choice and do the following:

```shell
npm install --global new-post-gatsby-starter-blog
```
then run

```shell
cd [your directory]
new-post "Title of post"
```

This will create a new post with the frontmatter scaffold appropriate for this starter.

## Issues?

See [Issues](https://github.com/twhite96/gatsby-starter-blog-new-post/issues).

## Suggestions?

Submit an issue or PR.

`LICENSE`: MIT.

