# hasabTech Blog

This repository contains blogs for hasabTech which will be posted on:
https://article.hasabtech.com

## Posting Articles

Create a **separate branch** first and then push your article in it.
Create a **Pull Request** for it to be added on the website.

### Branch Rules
Follow the following standard for creating a branch.
`author_article-name`

### Example
Considering `shameel_what-actually-is-git` as branch name

#### Creating Branch
`git branch shameel_what-actually-is-git`

#### Checking Out To Branch
`git checkout shameel_what-actually-is-git`


### Repo Rules

Create a separate repository for your the article where the repository name should reflect article name.

- Create `README.md` file which should contain the text.
- Create `images` directory which should contain the images used in the article.
  - Avoid using _external links_ for the images used in the article.

#### Example
Considering `Git - What Actually is VCS` to be the name of he repository
##### Folder Structure
```
+-- Git - What Actually is VCS
    +--README.md
    +--images
       +--image1.png
       +--image2.png
```
You can add customized name for images for better understanding purpose.

### Committing Rules

For posting Articles:

`[ARTICLE][post] - <Article-Name>`

For Editing Article:

`[ARTICLE][edit] - <Article-Name>`

For Fixing Something:

`[ARTICLE][fix] - <Article-Name>`

### Example
Note: Please follow the guidelines for creating branch first from `Branch Rules` headings and then follow following commands.
### Staging All Files
`git add .`
### Committing
`git commit -m "[ARTICLE][POST] - Git-What-Actually-Is-VCS"`
