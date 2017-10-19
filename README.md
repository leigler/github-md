# github-md

- github-md is a suuuuper basic single-page javascript application for Github Pages. 
- Uses showdown.js to parse the markdown files.

## set up

Include showdown.js + github-md.js

Call `githubMD`:

```javascript

	githubMD({	user: "leigler", 
				repository: "github-md",
				local: "false"
				})

```