
git add -A
git commit -m 'fix deport bug'
git pull origin public
git add -A
git commit -m 'fix depot bug'
git pull origin public
git push origin public
git push origin HEAD:public
git checkout public
git merge master
npm run build
npm run copy
