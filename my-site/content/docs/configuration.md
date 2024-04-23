+++
title = 'Configuration'
date = 2024-04-23T10:29:09+08:00
+++

# Create a site 
### Commands 

**Run these commands on a Git Bash terminal to create a new site with the "Ananke" theme.**

```
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo server
```

# Add content 
**Add a new page to your site.**

`hugo new content posts/my-first-post.md`

This creates a content/posts directory, with the `my-first-post.md` file in it.

# Start development server
To start the developemnt server, run this command. This allows the suer to view the changes of content on the site