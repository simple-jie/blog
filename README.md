# blog
git install
> brew install git

node install
> brew install node

hexo install
> npm install hexo-cli -g

run instance
> hexo s

deploy
> hexo d -g
if get error deployer not found:git 
> npm install hexo-deployer-git --save

new post
> hexo new post "post title"

deploy post
> hexo clean && hexo generate && hexo deploy
