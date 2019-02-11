# gatsby-remark-sectionize

This is a very simple wrapup of remark plugin [remark-sectionize](https://github.com/jake-low/remark-sectionize), so that it can be used in [Gatsby](https://www.gatsbyjs.org/) directly.

## Installation

```bash
yarn add --dev gatsby-transformer-remark gatsby-remark-sectionize
```

## Configuration

In `gatsby-config.js` file, write the following:

```javascript
{
  resolve: `gatsby-transformer-remark`,
  options: {
    plugins: [
      `gatsby-remark-sectionize`,
    ],
  },
}
```
