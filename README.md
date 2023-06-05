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
- Menubar
  - System Settings -> Clock Options -> display the time with seconds
  - remove
    - WIFI
    - spotlight
- Finder
  - Settings > Sidebar: check home locations

## Software

- Browser ([Microsoft Edge](https://www.microsoft.com/en-us/edge/download?form=MA13FJ))
  - set as default browser 
  - sign in for syncing
    - personal account & company account
  - [ ] config minimum style [你与清爽 Mac 版 Edge 浏览器还差一个配置文件的距离](https://sspai.com/post/77397)

- Key-mapping ([Karabiner-Elements](https://karabiner-elements.pqrs.org/))
  - import configuration file from [karabiner-configs repo](https://github.com/GymRat102/karabiner-configs)

- Window Manager([SizeUp](https://www.irradiatedsoftware.com/sizeup/))
  - start on Login
  - reset shortcuts:
    - Make Window Full Screen: option + command + F
    - Preferences > General > not Show Visual Action Overlay
  - a review article about alternatives: [7 款 Mac 窗口管理利器推荐，任务再多也不乱](https://www.ifanr.com/app/699275)

- Quick Launcher
  - Raycast
    - [ ] config
    - set up Quicklinks
  - [ ] Alfred

- Menu bar simplifier ([Hidden Bar](https://apps.apple.com/us/app/hidden-bar/id1452453066?mt=12))

- Dictionary ([Eudic](https://www.eudic.net/v4/en/app/eudic))
  - [] Download resources & config from Google Drive
    - Dictionary resources
    - Eudic config
  - set command+1 as hotkey

- Spaced Repetition ([Anki](https://apps.ankiweb.net/))

- Note
  - [Obsidian](https://obsidian.md/download)
    - Using [Nutstore](https://www.jianguoyun.com/s/downloads) for syncing
  - Notion

- Dock badge monitor ([Doll](https://github.com/xiaogdgenuine/Doll))

- Screenshot
  - [Xnip](https://apps.apple.com/us/app/xnip/id1221250572?mt=12)

- Shortcut tools
  - [Shortery](https://www.lgerckens.de/shortery/)

## Coding

- Command Line Tools (CLT) for Xcode
  - xcode-select --install
  - or automatic install prompt from iterm2
  - [ ] packed with git?

- Package Manager ([Homebrew](https://brew.sh/))

- Terminal Emulator ([iterm2](https://iterm2.com/downloads.html))
  - dark theme
  - [ ] requires pip3/command line developer tools installed
  - [ ] what magic does iterm2 do

- Zsh configuration manager - [Oh My Zsh]((https://ohmyz.sh/))
  - [autocompletion](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)
  - [plevel10k](https://github.com/romkatv/powerlevel10k#getting-started)
    - [font incompatible solution for editors](https://github.om/romkatv/powerlevel10k/blob/master/font.md)  

- Git Config
  - Basic configs ([GTB instructions](https://trello.com/c/JrAkQeDy/140-day01-%E9%85%8D%E7%BD%AE-git))
  - [Generate a new ssh key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) & [add ssh key to GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
  - [ ] config based on folder

- Editor
  - [IntelliJ IDEA]((https://www.jetbrains.com/idea/download/#section=mac))
    - [ ] create command-line launcher
    - Plugins
      - Idea-Vim plugin
        - [ ] .ideavimrc config
      - GitToolBox
  - [ ] Vim
  - [ ] VS Code

- SDK Manager ([SDKMAN!](https://sdkman.io/install))
  - select JDK to install: `sdk java list`

- Containerization
  - [OrbStack](https://orbstack.dev/download)

- API Client (Postman)

- Cloud and Kubernetes
  - az
    `brew install az`
  - openlens
    `brew install --cask openlens`
  - kubelogin
    `brew install Azure/kubelogin/kubelogin`
  - kubectl
    `brew install kubectl`

## Office-specific

- Zoom
- Wecom
- WeChat
- VMWare Horizon Client
