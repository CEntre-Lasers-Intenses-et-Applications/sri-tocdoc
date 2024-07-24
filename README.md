# tocdoc

## Testing

### Create a site

```bash
cd tocdoc
git checkout dev
git checkout -b testing
hugo new site Theremin
cd Theremin
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo server
```

### Add a new page to your site

```bash
hugo new content post/my-first-post.md
# Add some Markdown to the body os the post
# Save the file and start Hugo's development server
```
