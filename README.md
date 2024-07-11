<header align="center">
    <div align="center">
        <img src="mac.png" alt="Logo" width="250" />
    </div>
    <h1 align="center">Mac Dev Setup</h1>
    <p align="center">Simple setup with lot of goodies 🍎</p>
</header>

## Preferences

1. Enable **Trackpad** / **Tap to click**

2. Enable **Accessibility** / **Mouse and trackpad** / **Trackpad options** / **Enable dragging** / **Three finger drag**

3. Disable accent menu (needs restart):

```sh
defaults write -g ApplePressAndHoldEnabled -bool false
```

4. Move key repeat rate and delay until repeat all the way to the right

## Setup

1. Install [Brave](https://brave.com/download/).

2. Install [homebrew](https://brew.sh/). Also installs command line tools.

3. Install brew packages.

```sh
brew install git vim yarn wget watchman tree ffmpeg gh coreutils
```

4. Configure `git`:

```sh
git config --global user.name "First Last"
git config --global user.email email@email.com
```

5. Install [Cascadia Code](https://github.com/microsoft/cascadia-code#installation) font

6. Add [GPG](https://help.github.com/en/articles/managing-commit-signature-verification) and [SSH](https://help.github.com/en/articles/connecting-to-github-with-ssh) keys

7. Install `quick-look` plugins:

```sh
brew install qlcolorcode qlstephen qlmarkdown quicklook-json qlimagesize webpquicklook quicklookase qlvideo --cask
```

### CLI

1. Install [Oh my ZSH](https://github.com/robbyrussell/oh-my-zsh)

2. Install [dotfiles](https://github.com/divyanshu013/dotfiles/)

3. Install [asdf](https://github.com/asdf-vm/asdf?tab=readme-ov-file#documentation)

#### CLI plugins

- [Fig](https://fig.io/) - modern terminal autocomplete
- [ZSH autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)
- [bgnotify](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/bgnotify)
- [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)
- [z](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/z)
- [fzf](https://github.com/junegunn/fzf)
- [fkill-cli](https://github.com/sindresorhus/fkill-cli)
- [fx](https://github.com/antonmedv/fx)
- [bat](https://github.com/sharkdp/bat#on-macos-or-linux-via-homebrew)
- [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy)
- [pgcli](https://www.pgcli.com/)
- [mycli](https://www.mycli.net/)
- [ag](https://github.com/ggreer/the_silver_searcher)
- [cleanup](https://github.com/fwartner/mac-cleanup)
- [sudo](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/sudo)
- [web-search](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/web-search)
- [jay](https://github.com/nikersify/jay)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - improved `youtube-dl`
- [pnpm](https://pnpm.io/installation)

### Browsers

- [Firefox](https://www.mozilla.org/en-US/firefox/mac/)
- [Brave](https://brave.com/download/)

#### Extensions

- Bitwarden
- Dark Reader
- File icons for GitHub and GitLab
- Keepa
- Lighthouse
- Markdown Here
- MetaMask
- Minimal Theme for Twitter / X
- Phantom
- Raindrop.io
- React Developer Tools
- Reddit Enhancement Suite
- Wikiwand
- [SponsorBlock](https://github.com/ajayyy/SponsorBlock) - auto skips YouTube sponsors

### Utils

- [TickTick](https://ticktick.com/download) - task management
- [Raycast](https://www.raycast.com/) - spotlight and alfred alternative
- [Dato](https://sindresorhus.com/dato) - better date menu bar app
- [Bandwidth+](https://apps.apple.com/us/app/bandwidth/id490461369?mt=12) - bandwidth monitoring
- [Sensible side button](https://sensible-side-buttons.archagon.net/) - for gaming mouse
- [Scroll reverser](https://pilotmoon.com/scrollreverser/) - auto scroll reverse on mouse
- [Itsycal](https://www.mowglii.com/itsycal/) - view calendar from menu bar
- [KeepingYouAwake](https://github.com/newmarcel/KeepingYouAwake) - prevent mac from sleeping
- [Lungo](https://sindresorhus.com/lungo) - prevent mac from sleeping
- [Maccy](https://github.com/p0deje/Maccy) - clipboard manager
- [Rectangle](https://rectangleapp.com/) - window manager
- [Kap](https://getkap.co/) - screen recorder
- [Mounty](https://mounty.app/) - NTFS volumes in write mode
- [Thor](https://apps.apple.com/cn/app/thor/id1120999687?l=en&mt=12) - painless application switching
- [Dozer](https://github.com/Mortennn/Dozer) - hide menu bar icons
- [Android File Transfer](https://www.android.com/filetransfer/) - for android phones
- [Pock](https://pock.dev/) - touchbar dock
- [MTMR](https://github.com/Toxblh/MTMR) - touchbar customizations
- [Markdown here](https://github.com/adam-p/markdown-here) - email in markdown
- [Mos](https://github.com/Caldis/Mos) - smooth scrolling with external mouse
- [Flotato](https://flotato.com/) - turn any webpage into floating app
- [Background Music](https://github.com/kyleneideck/BackgroundMusic) - auto pause music
- [QRCP](https://github.com/claudiodangelis/qrcp) - share files to and fro another device through QR code
- [Latest](https://github.com/mangerlahn/latest) - check for all apps updates
- [OneMenu](https://www.withmarko.com/one-menu) - menu bar app for checking resource utilization, quick window management, keyboard cleaning

### Dev

- [iTerm](https://iterm2.com/) - terminal
- [VSCode](https://code.visualstudio.com/download) - code editor
- [GPG Suite](https://gpgtools.org/) - gpg manager
- [Xcode](https://apps.apple.com/in/app/xcode/id497799835?mt=12) - react native stuff
- [Android Studio](https://developer.android.com/studio) - react native stuff
- [React Native Debugger](https://github.com/jhen0409/react-native-debugger/) - react native debugging
- [Table Plus](https://tableplus.io/) - the DB app
- [Sequel Pro](https://www.sequelpro.com/) - MySQL client
- [Postgres app](https://postgresapp.com/downloads.html) - Postgres for mac
- [Postico app](https://eggerapps.at/postico/) - Postgres client
- [MongoDB app](https://github.com/gcollazo/mongodbapp) - MongoDB for mac
- [Redis app](https://github.com/jpadilla/redisapp) - Redis for mac
- [Contraste](https://contrasteapp.com/) - simple color contrast ratio viewer
- [Medis](https://github.com/luin/medis) - redis client
- [Proxyman](https://proxyman.app/) - proxy client for apps
- [brew-services-menubar](https://github.com/andrewn/brew-services-menubar) - managing brew services from menubar
- [ngrok](https://ngrok.com/download) - localhost tunnel
- [RunJS](https://runjs.dev/) - JS runtime desktop app that executes as you type
- [Hoppscotch](https://hoppscotch.io/) - API Client

### Music

- [SpotMenu](https://github.com/kmikiy/SpotMenu) - spotify and itunes menubar app
- [Spotify](https://www.spotify.com/us/download/mac/) - best music app
- [LyricsX](https://github.com/ddddxxx/LyricsX) - song lyrics

### Apps

- [Obsidian](https://obsidian.md/download)
- [Raindrop](http://raindrop.io/) - all my bookmarks
- [Zoom](https://zoom.us/download#client_4meeting) - video calls
- [Black Out](https://apps.apple.com/no/app/black-out/id1319884285) - hide sensitive information on images
- [Dropbox](https://www.dropbox.com/downloading) - cloud storage
- [Discord](https://discordapp.com/api/download?platform=osx) - chat client
- [Telegram](https://telegram.org/) - chat client
- [Figma](https://www.figma.com/downloads/) - design software
- [IINA](https://iina.io/) - media player
- [Pym](https://apps.apple.com/in/app/pym/id1451733095?mt=12&app=apps&ign-mpt=uo%3D4) - image compression
- [Davinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/) - video editing
- [Clocker](https://apps.apple.com/us/app/clocker-menubar-world-clock/id1056643111?mt=12) - timezones menubar app
- [Flip clock screensaver](https://fliqlo.com/#/screensaver) - nice screensaver
- [Notion](https://www.notion.so/desktop/mac-universal/download)
- [WhatsApp](https://www.whatsapp.com/download/)
- [Signal](https://signal.org/download/)
- [Slack](https://slack.com/downloads/mac)
- [Kindle](https://www.amazon.com/b?ie=UTF8&node=16571048011)
- [Darkroom](https://apps.apple.com/us/app/darkroom-photo-video-editor/id953286746) - photo editing

## Related

- [Linux dev setup](https://github.com/divyanshu013/linux-dev-setup)
- [Mac dev setup](https://github.com/divyanshu013/mac-dev-setup)
- [Dotfiles](https://github.com/divyanshu013/dotfiles)

## Author

- [@divyanshu013](https://twitter.com/divyanshu013) 👋

### Attributions

<div>Icons made by <a href="https://www.flaticon.com/authors/flat-icons" title="Flat Icons">Flat Icons</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>
