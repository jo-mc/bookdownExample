# bookdownExample
make a bookdown in gtihub

following:
https://bookdown.org/yihui/bookdown/github.html

One approach is to publish your book as a GitHub Pages site from a /docs folder on your master branch as described in GitHub Help. 
First, set the output directory of your book to be /docs by adding the line output_dir: "docs" to the configuration file _bookdown.yml. Then, after pushing your changes to GitHub, go to your repository’s settings and under “GitHub Pages” change the “Source” to be “~~master~~ main branch /docs folder”. In this case, the .nojekyll file has to be in the /docs folder.  
note: Git now uses main rather than master.

github help:
https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

So create a repository on your computer, have a docs folder or whatever, add you html pages, add files to repository git add *.html + whatever else: css, js,  figures etc
create the repository on github and dont create readme, then it should give you a link to use on your computer to create the repository from your computer data.
git push origin master, and you should see your files in github, (and create a file .nojekyll where your html index.html is located on your camputer add it to git git add .nojekyll - include directory if not in folder)

then on gitub go to Setings (next to insights) on row of commands scroll down to github pages, change source to main? (unles you have pages in another branch) and that should be it.
hmm I went out and then back into settings scroll down again to github pages, and you can see the link for where your pages will be..  (maybe it was there after I did last step but did not notice?) then click and you should see your page.
