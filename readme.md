Repo Steps : 
* Install Hugo : https://gohugo.io/getting-started/installing/
* Clone Repo -> cd into repo
* run : hugo server -D


All Basic Steps :
* Install Hugo : https://gohugo.io/getting-started/installing/
* Verify installation : hugo version
* Create new site : hugo new site quickstart
* Add a theme : cd quickstart
                git init
                git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
* add theme to site config : echo 'theme = "ananke"' >> config.toml
* create first post : hugo new posts/my-first-post.md
* start server : hugo server -D

For building on netlify :
* create netlify.toml
* change "base_url" in config to the one given by netlify to fix styling
