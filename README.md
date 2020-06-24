# javascript tools chain

## base tools
[macos](http://apple.com/macos) or [windows](https://www.microsoft.com/zh-cn/windows)   
[chrome](https://www.google.cn/chrome/index.html)  
[nodejs](https://nodejs.org/)  
[npmjs](https://www.npmjs.com/)  
[bash](https://www.gnu.org/software/bash/)  
[nvm](https://github.com/nvm-sh/nvm#installing-and-updating) -- manage node version  
[git](https://git-scm.com/) --- muti programer collaboration   
[nrm](https://github.com/Pana/nrm)
- manage npm mirror
- install from npm global, follow command `npm -i nrm` 
- dependence version control

[semver](http://caibaojian.com/npm/misc/semver.html)   
推荐package.json中使用^符号，同步更新package-lock.json文件    
[vscode](https://code.visualstudio.com/)

#### plugins recommend

- gitlens
- Auto Rename Tag
- eslint
- Path Intellisense
- Bracket Pair Colorizer
- Visual Studio IntelliCode  
- EditorConfig for VS Code  
- remote explorer
- docker
- Polacode

tips: Enable the terminal `code` command with mac os: open VS Code and type CMD+SHIFT+P and type “shell command” and select “Install ‘code’ command in PATH”.

## git hooks
[husky](https://github.com/typicode/husky#readme) + [lint-staged](https://github.com/okonet/lint-staged#readme)

## test
[jest](https://jestjs.io/)   

## code style
[eslint](https://eslint.org/) + [prettier](https://prettier.io/) + [editorconfig](https://editorconfig.org/)

#### why eslint + prettier + **editorconfig**
Prettier和Linter系列比如ESLint的区别在于Prettier是一个专注于代码格式化的工具，对代码不做质量检查。  
 .editorconfig不光可以检验js文件的代码风格，还可以对.md等文件进行代码风格控制。Eslint和.editorconfig并不冲突，同时配合使用可以使代码风格更加优雅。
  
#### tips

- eslint-loader options: { cache: true  }

这里如果没有用precommit保证代码仓库的代码是干净的，需要设置为false

- [browserslist](https://github.com/browserslist/browserslist)

在package.json中使用browserslit配置，方便front-end tools共享目标环境

#### referrence
[Prettier vs. Linters](https://prettier.io/docs/en/comparison.html)   
[whats-the-difference-between-eslint-and-prettier](https://restishistory.net/blog/whats-the-difference-between-eslint-and-prettier.html)   
[why you should use eslint prettier editorconfig together](https://blog.theodo.com/2019/08/why-you-should-use-eslint-prettier-and-editorconfig-together/)

## build tools 
webpack for app<br />rollup for library

#### referrence
[webpack vs rollup vs parcel](https://medium.com/js-imaginea/comparing-bundlers-webpack-rollup-parcel-f8f5dc609cfd)   
[rollup zhihu](https://www.zhihu.com/search?q=rollup&utm_content=search_history&type=content)




