![Stats](https://github-readme-stats.vercel.app/api?username=willfolsom&count_private=true&show_icons=true&bg_color=30,1f2938,000&hide_title=true&disable_animations=true&&line_height=24&title_color=fff&icon_color=0f0&text_color=fff)
![Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=willfolsom&layout=compact&bg_color=30,1f2938,000&hide_title=true&text_color=fff)

### 🕹️ Protips
+ Serve your sites locally when doing simple local web development to bypass CORS issues and such. Run this in the base directory of whatever you're working on (instead of opening index.html): ```python -m SimpleHTTPServer 8080```
+ Clean install your Node modules: ```rm -rf node_modules; npm i```
+ I use [Cmder](https://cmder.net/) as my Windows terminal.
+ [Spectacle](https://github.com/eczarny/spectacle) (on Macs) is a must.
+ See your installed VSCode extensions with ```code --list-extensions | xargs -L 1 echo```. [I use all of these.](https://gist.github.com/willfolsom/cc712a2fa6ae84ccc85736382911fb01)
+ [Quick tips on using Mockito Fakes, Stubs, Mocks, and Spys](https://gist.github.com/willfolsom/6ed3f2affe92a425c8c13d73f120be86#file-mockito-fakes-stubs-mocks-and-spys)
+ [Use tput and variables to make shell script output cooler](https://gist.github.com/willfolsom/f927436a3c695b874bc7349359c9f745)
+ Use `console.table({someObject})` instead of logs

### 💾 Git / Github
+ Change your email per Git repo: ```git config user.email "whatever@cool.com"```
+ Rollback commits: ```git reset HEAD~{number to rollback}```
+ ```git clean -dfX``` will remove untracked directories and files (forcefully) from the working tree that are ignored by Git.
+ See git blame line numbers per author per repo. Run: ```git ls-tree -r -z --name-only HEAD | xargs -0 -n1 git blame --line-porcelain HEAD |grep  "^author "|sort|uniq -c|sort -nr``` (it can be slow)
+ Add GitHub actions badges to a Readme (the workflow name is in the .yml, i.e. "Go", "Android", etc):<br/> ```![](https://github.com/{owner}/{repo}/workflows/{workflow_name}/badge.svg?branch={targeted_branch})```
+ I use [zsh-completions](https://formulae.brew.sh/formula/zsh-completions) so that I have tab completions specifically for Git branches and npm run scripts.
+ [.zshrc for showing current Git branch](https://gist.github.com/willfolsom/43d26018be685c651968431124a79906), e.g.:<br/>![](https://user-images.githubusercontent.com/3690251/101680903-5cd0e500-3a2f-11eb-8bbc-82b6888b51c7.png)<br/>
```curl https://gist.githubusercontent.com/willfolsom/43d26018be685c651968431124a79906/raw/3f6bc3976448134f14e6cca2d68a71b85eb32b0a/.zshrc -so .zshrc```

### 🖲️ Links
+ [Mentoring via Superpeer](https://superpeer.com/willfolsom)
+ [Cool projects from college](https://cargocollective.com/willfolsom)
+ [Codepen](https://codepen.io/willfolsom)
+ [Exercism Profile](https://exercism.io/profiles/willfolsom)
+ [More stats here](https://profile-summary-for-github.com/user/willfolsom)
+ Koans:
  + [![Go](https://github.com/willfolsom/go-koans/workflows/Go/badge.svg)](https://github.com/willfolsom/go-koans/)
  + [![Python](https://github.com/willfolsom/python_koans/actions/workflows/main.yml/badge.svg)](https://github.com/willfolsom/python_koans)

![](https://komarev.com/ghpvc/?username=willfolsom&color=ff69b4&label=views&style=flat) ![](https://hit.yhype.me/github/profile?user_id=3690251) 
