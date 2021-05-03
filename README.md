# personal web (concept please check [site](https://robertchu1205.github.io/))
## github action
- triggered by tag
    - **develop** branch
        - auto create md with quotes from fortune in the posts
        - calculate new dev version and save it to .env
    - **dev** branch
        - commit and push to **staging** branch 
        - save staging version from tag or .env to .env
    - **staging** branch 
        - release the web of **staging** version to [REPO](https://github.com/robertchu1205/robertchu1205.github.io)
## static site generator chosen
### Why Hugo, not Jekyll
- more straightforward (installing themes and itself)
- binary (easier) installation
- faster builds
- Go built
- built-in live reload server
- Useful Features (e.g. Menus, sitemaps)
- Thriving community (The most Github stars in all static site generator)

### Why [Erblog](https://themes.gohugo.io/erblog/) as theme
- mobile responsive
- posts showed in the landing pages

## Why only github actions, github pages used
- simple and clean system with less tools
- functions strong and documents solid

## Workflows as below
![](/static/img/workflows.jpeg)