# mac-migration
My checklist for new macOS machine

---

## Mac Settings

- Dock
  - No System Apps
  - Left Dock & Adjust Size
  - No recent apps shown
  - [Add dock spacer](https://chrispennington.blog/blog/add-spacer-in-macos-dock/)
- Trackpad
  - Tap to click
- Function Keys
  - Use F1, F2 keys as standard function keys

## Software

- Browser ([Microsoft Edge](https://www.microsoft.com/en-us/edge/download?form=MA13FJ))
  - sign in for syncing
    - personal account & company account
  - [ ] config minimum style [你与清爽 Mac 版 Edge 浏览器还差一个配置文件的距离](https://sspai.com/post/77397)

- Key-mapping ([Karabiner-Elements](https://karabiner-elements.pqrs.org/))
  - import configuration file from [karabiner-configs repo](https://github.com/GymRat102/karabiner-configs)

- Window Manager([SizeUp](https://www.irradiatedsoftware.com/sizeup/))
  - a review article about alternatives: [7 款 Mac 窗口管理利器推荐，任务再多也不乱](https://www.ifanr.com/app/699275)

- [ ] Alfred

- Menu bar simplifier ([Hidden Bar](https://apps.apple.com/us/app/hidden-bar/id1452453066?mt=12))

- Dictionary ([Eudic](https://www.eudic.net/v4/en/app/eudic))
  - [ ] Dictionary resources
  - [ ] Eudic config

- Spaced Repetition ([Anki](https://apps.ankiweb.net/))

## Coding

- Command Line Tools (CLT) for Xcode
  - xcode-select --install
  - or automatic install prompt from iterm2
  - [ ] packed with git?

- Package Manager ([Homebrew]([url](https://brew.sh/)))

- Terminal Emulator ([iterm2](https://iterm2.com/downloads.html))
  - dark theme
  - [ ] requires pip3/command line developer tools installed
  - [ ] what magic does iterm2 do

- Zsh configuration manager - [Oh My Zsh]([url](https://ohmyz.sh/))
  - [autocompletion](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)
  - [plevel10k](https://github.com/romkatv/powerlevel10k#getting-started)
    - [font incompatible solution for editors](https://github.com/romkatv/powerlevel10k/blob/master/font.md)  

- Git Config
  - Basic configs ([GTB instructions]([url](https://trello.com/c/JrAkQeDy/140-day01-%E9%85%8D%E7%BD%AE-git)))
  - [Generate a new ssh key]([url](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)) & [add ssh key to GitHub]([url](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account))
  - [ ] config based on folder

- Editor
  - [IntelliJ IDEA]([url](https://www.jetbrains.com/idea/download/#section=mac))
    - [ ] create command-line launcher
    - Idea-Vim plugin
      - [ ] .ideavimrc config
  - [ ] Vim
  - [ ] VS Code

- SDK Manager ([SDKMAN!](https://sdkman.io/install))
  - select JDK to install: `sdk java list`

- Containerization
  - [OrbStack](https://orbstack.dev/download)

- API Client (Postman)

## Office-specific

- Zoom
- Wecom
- WeChat
- VMWare Horizon Client
