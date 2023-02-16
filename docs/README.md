```shell
cd /usr/local/Homebrew/Library/Taps
https://mirrors.tuna.tsinghua.edu.cn/help/homebrew/

https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-core.git
git clone https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-core.git
git clone git@github.com:Homebrew/homebrew-core.git
https://github.com/Homebrew/homebrew-services
https://github.com/melonamin/homebrew-formulae

# 从本镜像下载安装脚本并安装 Homebrew / Linuxbrew
git clone --depth=1 https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/install.git brew-install
/bin/bash brew-install/install.sh
rm -rf brew-install

# 也可从 GitHub 获取官方安装脚本安装 Homebrew / Linuxbrew
/bin/bash -c "$(curl -fsSL https://github.com/Homebrew/install/raw/master/install.sh)"

export HOMEBREW_API_DOMAIN="https://mirrors.tuna.tsinghua.edu.cn/homebrew-bottles/api"
export HOMEBREW_BOTTLE_DOMAIN="https://mirrors.tuna.tsinghua.edu.cn/homebrew-bottles"
export HOMEBREW_BREW_GIT_REMOTE="https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/brew.git"
export HOMEBREW_CORE_GIT_REMOTE="https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-core.git"
export HOMEBREW_PIP_INDEX_URL="https://pypi.tuna.tsinghua.edu.cn/simple"



// 替换brew.git:
cd "$(brew --repo)"
git remote set-url origin https://mirrors.ustc.edu.cn/brew.git

// 替换homebrew-core.git:
cd "$(brew --repo)/Library/Taps/homebrew/homebrew-core"
git remote set-url origin https://mirrors.ustc.edu.cn/homebrew-core.git

// 替换homebrew-cask.git:
cd "$(brew --repo)"/Library/Taps/homebrew/homebrew-cask 
git remote set-url origin https://mirrors.ustc.edu.cn/homebrew-cask.git

https://unpkg.com/axios/dist/axios.min.js
```

```
Error: Node Sass does not yet support your current environment
```