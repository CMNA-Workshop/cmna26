This is the repository for the website for CMNA'26.

The site is built using Hugo and the "PaperModX" theme. The generated site is built into the 'docs' folder to ease deployment to GitHub Pages.

If you want to rebuild the site:

* Install [Hugo](https://gohugo.io/) for your platform, i.e. `$ brew install hugo` (It's also available on Linux and Windows)
* Clone this repo
* Make your changes, probably in the content folder which contains information about all the site pages. More rarely in the static/assets/ folder, and even more rarely in the config.toml. Everything else needn't be touched too often.
* Preview your changes locally using $ hugo server on, e.g. localhost:1313 (Hugo will tell you which port to use)
* If you're happy with the preview then generate your site (automatically into the docs folder) using `$ hugo`
* Add & Commit to the repo the push your changes
* Then visit the live deployment [here](https://cmna-workshop.github.io/cmna26/)



