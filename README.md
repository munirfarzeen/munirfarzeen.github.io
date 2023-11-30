

3. Run `hugo` in the `pwd`. This will build the website locally
4. To watch on localhost, run `hugo server --watch`. This is will give a localhost link.



## Deploying
`Note: Verify locally first and then push to github`

1. Run `hugo` in `pwd`, after editing the files. This will generate the `public` folder, which is then used for the deployment.
2. Steps to push local data to the remote
```
git checkout main
git add .
git commit -m " updated"
git push origin main
```
3. We are using `gh-pages` for the deployment.
```
git checkout  gh-pages
git fetch origin gh-pages
git rm -rf .
git checkout main -- 'public/*'
mv -f public/* .
rm -r public
git add .
git commit -m "updated"
git push origin gh-pages
```
