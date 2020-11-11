# bookdownExample
make a bookdown in gtihub

following:
https://bookdown.org/yihui/bookdown/github.html

One approach is to publish your book as a GitHub Pages site from a /docs folder on your master branch as described in GitHub Help. 
First, set the output directory of your book to be /docs by adding the line output_dir: "docs" to the configuration file _bookdown.yml. Then, after pushing your changes to GitHub, go to your repository’s settings and under “GitHub Pages” change the “Source” to be “~~master~~ main branch /docs folder”. In this case, the .nojekyll file has to be in the /docs folder.  
note: Git now uses main rathre than master.

github help:
https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
