# blog

### Install
```
brew install hugo # check https://gohugo.io/getting-started/installing/ for alternative method
git clone https://github.com/monitory/blog.git
cd blog
hugo server -D # launch a server and serve it at http://localhost:1313/
```

### New post
```
hugo new "posts/my-post.md"
```

### Structure
- `content` is where we edit posts
- `docs` is where all generated files ends up
- We use the [meme](https://github.com/reuixiy/hugo-theme-meme) theme. 


### Deploy

`sh deploy.sh`

