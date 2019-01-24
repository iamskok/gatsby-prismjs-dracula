<a href="https://gatsbyjs.org">
	<p align="center">
		<img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="120" />
	</p>
</a>

<h1 align="center">
	Dracula Theme for Gatsby
</h1>

<a href="https://draculatheme.com">
	<p align="center">
		<img alt="Gatsby" src="https://draculatheme.com/assets/img/dracula.gif" width="350" />
	</p>
</a>

All in one dark theme for [`gatsby-remark-prismjs`](https://www.gatsbyjs.org/packages/gatsby-remark-prismjs) plugin with syntax and line highlighting, line numbers, [file title](https://github.com/DSchau/gatsby-remark-code-titles) and [copy button](https://github.com/iamskok/gatsby-remark-code-buttons).

## Installation

```bash
npm install gatsby-prismjs-dracula
```

```js
// gatsby-browser.js
import 'gatsby-prismjs-dracula';
```

## FAQ

* To show line numbers add `{showLineNumbers: true}` in the code block, like [this](https://www.gatsbyjs.org/packages/gatsby-remark-prismjs/#line-numbering) or set them globally by adding `showLineNumbers: true` in `gatsby-remark-prismjs` [options](https://www.gatsbyjs.org/packages/gatsby-remark-prismjs/#how-to-use).

* To add line highlights check out this [article](https://using-remark.gatsbyjs.org/code-and-syntax-highlighting/#line-highlighting--numbering)

* To add button text, tooltip text or to change icon refer to `gatsby-remark-code-buttons` [options](https://github.com/iamskok/gatsby-remark-code-buttons#options) section.

---

[PRs are welcome](https://github.com/iamskok/gatsby-prismjs-dracula/fork) :octocat:
