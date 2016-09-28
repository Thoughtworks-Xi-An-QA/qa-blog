

```
npm install hexo-cli -g
进入repo
npm install
npm install hexo-deployer-git --save
hexo new 你要建立的blog
用markdown编辑器更改source/_posts/下的文章
编辑完成后 hexo g
然后
hexo d
推送到git

记着push完成后，
git pull -r
git add .
提交咱们blog repo 这样可以避免repo有冲突
git commit -m ""
git push origin master
```
