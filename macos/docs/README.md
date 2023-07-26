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

brew search docker
brew install docker
docker --version
brew info docker

docker search redis
docker pull redis:latest
docker images

docker run --name redis-jarvan -p 6379:6379 -d --restart=always redis:latest redis-server --appendonly yes --requirepass '123456'

brew cask install docker

brew unlink boost

To force the link and overwrite all conflicting files:
  brew link --overwrite boost

To list all files that would be deleted:
  brew link --overwrite --dry-run boost
```

```
Error: Node Sass does not yet support your current environment

Visit the Llama repository in GitHub and follow the instructions in the README to run the download.sh script.
When asked for your unique custom URL, please insert the following:
https://download.llamameta.net/*?Policy=eyJTdGF0ZW1lbnQiOlt7InVuaXF1ZV9oYXNoIjoiXHUwMDBmUj8mPn8%7EPyIsIlJlc291cmNlIjoiaHR0cHM6XC9cL2Rvd25sb2FkLmxsYW1hbWV0YS5uZXRcLyoiLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE2ODk5MzMwMzd9fX1dfQ__&Signature=icvE0UYIjADwbPD2uRrbcJX%7EOwUkrvabeGEhSTn1fzawqI01dpO6C2weAQrN7rjor7VmgV8-MdpKKI58zFjsIyAUNzm%7E6q%7E2g7uy%7EF4lSUn9XpFrK3Mr8mP2Hr1YKG2A9dhBYawcEFPsAdX9t7OyFDr%7EenQJlX7VnhrmaQDJE9MjbHXncQYoSd45XFCGgGlYuR9%7Ez75DPTjUME7XSd4L8Wpw6rH0uw4qvOlK6V6JbNF0bzNfbnzZixPtuj%7EGocsAPR8BKAFIm0w4NLMZKdLMzXjJ%7EalihawwfpI%7E2sctZUoDIJXDmx7V3ZAgIuIfB2o9rKF-wN4Gdw2tfFxSok%7Ewrw__&Key-Pair-Id=K15QRJLYKIFSLZ
Select which model weights to download

Visit the Llama repository in GitHub and follow the instructions in the README to run the download.sh script.
When asked for your unique custom URL, please insert the following:
https://download.llamameta.net/*?Policy=eyJTdGF0ZW1lbnQiOlt7InVuaXF1ZV9oYXNoIjoiPz9RJ1FcdTAwMTJcXD8iLCJSZXNvdXJjZSI6Imh0dHBzOlwvXC9kb3dubG9hZC5sbGFtYW1ldGEubmV0XC8qIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxNjkwMzYyNTM2fX19XX0_&Signature=aqmuAYs3MpWTcBT4ppClMOMjVplCCpqlPDat-ZfZFhMZC5Nf1NvIsfT7jjM%7EVeNxscLTSZ7HGZg9NVjcPuTSgz6GARBe1-5gBRjsdn2Jq63w8CB6rGPe9R4MTukf5ejDIvYPaphxwlLc3IDSR7TABS7vTo3UzBFWR3eIb9qNL-lboHnZM5c2UHC1NmB0rbCPifg1ERMB765qb1ZSv2FBhQnCs7QpEJQyOAuM4%7ExWN-SFTeJ1q1EmIgEWJbdGEoAzq9qwv4UE1TCQ0qrHGc6wNG2mBm401RQFjmx7ojCfUTRs10gx15JA02CSJz68FbdAYDw0D5VEBECRBRgNhf8asA__&Key-Pair-Id=K15QRJLYKIFSLZ
Select which model weights to download
```
