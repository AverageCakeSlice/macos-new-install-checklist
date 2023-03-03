# New Install Checklist (MacOS Ventura 13.2)

## Prelude - Setup Wizard & Settings
- Setup Wizard
    - Sign-in with Apple ID
    - Setup Touch ID
    - Enable Find My
    - Disable Siri
- Software Updates
    - Install Xcode CLI tools 
        - `$ xcode-select --install`
    - Install all available system updates <sup>✨</sup>
- System Preferences & Hardware Changes
    - Mouse
        - Disable mouse acceleration  <sup>✨</sup>
            - `$ defaults write .GlobalPreferences com.apple.mouse.scaling -1`
        - Disable natural scrolling
            - System Preferences -> Mouse -> Natural Scrolling
    - Dock
        - Auto-hide the Dock  <sup>✨</sup>
            - System Preferences -> Desktop & Dock -> Automatically hide and show the Dock

## Essentials
- Install [HomeBrew](https://brew.sh/) <sup>✨</sup>
    - `$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- Install your preferred web browser 
    - I use [Brave](https://brave.com/download/) [🍺: `brave-browser`]
    - See [Browser Config & Extensions](#browser-config--extensions) if you want to take care of this right away
- Install [1Password desktop client](https://1password.com/downloads/mac/) [🍺: `1password`] <sup>♻️✨</sup>
- Install [Magnet](https://apps.apple.com/us/app/magnet/id441258766?mt=12) <sup>🛄💰✨</sup>
    - Configure keybinds according to monitor config and preference
- Install [PasteBot](https://tapbots.com/pastebot/buy/) [🍺: `pastebot`] <sup>🛄💰✨</sup>
- Install [Bartender](https://www.macbartender.com/Bartender4/purchase.html) [🍺: `bartender`] <sup>🛄💰✨</sup>
- Install [Logi Options+](https://www.logitech.com/en-us/software/logi-options-plus.html)
- Install a terminal emulator of choice
    - [Warp](https://app.warp.dev/get_warp) [🍺: `warp`] <sup>✨</sup>
    - [iTerm2](https://iterm2.com/downloads.html) [🍺: `iterm2`]
- Install [oh-my-zsh](https://ohmyz.sh/#install) <sup>✨</sup>
    - `$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
    - Install and configure the [Powerlevel10k theme](https://github.com/romkatv/powerlevel10k) <sup>✨</sup>

## Browser Config & Extensions
- Install the [1Password browser extension](https://1password.com/downloads/browser-extension/)✨
- Install the [Vue Devtools extension](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en)
- Install [Imagus](https://chrome.google.com/webstore/detail/imagus/immpkjjlgappgfkkfieppnmlhakdmaab?hl=en) <sup>✨</sup>
- Enable browser sync/sign-in if available
- Set the default search engine to your preference
- Disable browser password saving prompts
- Enable extensions for incognito/privacy mode
- Configure devtools to open in a new window
- Setup work and personal profiles browsers with multi-profile support <sup>✨</sup>

## Email, Calendar, and Contacts
- Setup email accounts in System Preferences
    - System Preferences -> Internet Accounts -> Add Acccount...
- Install a third-party email client if you prefer (I just use the vanilla Mail app)
    - [Spark](https://sparkmailapp.com/download) <sup>💸♻️</sup>
    - [Canary Mail](https://apps.apple.com/us/app/canary-mail/id1236045954) <sup>🛄💸♻️</sup>
    - Outlook (Installed with the O365 suite)
- Install [Fantastical](https://flexibits.com/fantastical)<sup>♻️✨</sup>

## Core Tools
- Install [Jetbrains Toolbox](https://www.jetbrains.com/toolbox-app/) [🍺: `jetbrains-toolbox`] <sup>✨</sup>
    - Install Webstorm <sup>♻️✨</sup>
    - Install Rider <sup>♻️✨</sup>
    - Install Pycharm <sup>✨</sup>
        - Community edition is free for personal use
    - Install DataGrip <sup>♻️✨</sup>
    - Install Fleet
    - Enable settings sync for all IDE's <sup>✨</sup>
- Install the [.NET SDK](https://dotnet.microsoft.com/en-us/download/visual-studio-sdks)
    - .NET 7 (Stable) [🍺: `dotnet`]
    - .NET 6 (LTS, Stable) [🍺: `dotnet@6`] <sup>✨</sup>
- Install [pyenv](https://github.com/pyenv/pyenv) [🍺: `pyenv`] <sup>✨</sup>
    - Follow the setup instructions closely, this needs a moderate amount of configuration
- Install [Node Version Manager (NVM)](https://github.com/nvm-sh/nvm) [🍺: `nvm`] <sup>✨</sup>
    - Install Node LTS <sup>✨</sup>
    - Install latest Node 16 release
    - `$ nvm install <version>`
    - `$ nvm use <version>`
- Install [Azure Data Studio](https://azure.microsoft.com/en-us/products/data-studio) [🍺: `azure-data-studio`]
    - Install your preferred extensions
- Install [Azure Storage Explorer](https://azure.microsoft.com/en-us/products/storage/storage-explorer) [🍺: `microsoft-azure-storage-explorer`]
- Install [VSCode](https://code.visualstudio.com/) [🍺: `visual-studio-code`] <sup>✨</sup>
    - Install your preferred extensions
- Install [PostMan](https://www.postman.com/downloads/) [🍺: `postman`] <sup>💸♻️✨</sup>
- Install [GitKraken](https://www.postman.com/downloads/) [🍺: `gitkraken`] <sup>♻️✨</sup>

## Communication
- Install [Slack](https://slack.com/downloads/mac)  [🍺: `slack`] <sup>💸♻️</sup>
- Install [Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams/download-app)  [🍺: `microsoft-teams`]
- Install [Telegram Desktop](https://desktop.telegram.org/)  [🍺: `telegram-desktop`] <sup>💸♻️✨</sup>
- Install [Discord](https://discord.com/download)  [🍺: `discord`] <sup>💸♻️</sup>


## Media
- Install [Spotify](https://www.spotify.com/us/download/other/) [🍺: `spotify`] <sup>💸♻️</sup>
- Install [SpotMenu](https://kmikiy.github.io/SpotMenu/) [🍺: `spotmenu`] <sup>✨</sup>
- Install [Overcast](https://apps.apple.com/us/app/overcast/id888422857) <sup>🛄🍎💸♻️✨</sup>
- Install [iina](https://iina.io/) [🍺: `iina`]  <sup>✨</sup>

## Personalization
- Install [Fresco](https://apps.apple.com/us/app/fresco/id1251572132?mt=12) <sup>🛄✨</sup>

## Maker Utilities
- Install [BalenaEtcher](https://www.balena.io/etcher) [🍺: `balenaetcher`] 
- Install [Raspberry Pi Imager](https://www.raspberrypi.com/software/) [🍺: `raspberry-pi-imager`]
- Install [PrusaSlicer](https://www.prusa3d.com/page/prusaslicer_424/) [🍺: `prusaslicer`] <sup>✨</sup>
- Install [Shapr3D](https://www.shapr3d.com/) [🍺: `shapr3d`] <sup>♻️✨</sup>

## Additional Utilities
- Install [Cyberduck](https://apps.apple.com/us/app/cyberduck/id409222199?mt=12) <sup>🛄✨</sup>
- Install [Parallels](https://www.parallels.com/products/desktop/) [🍺: `parallels`] <sup>♻️</sup>
- Install [Parsec](https://parsec.app/downloads) [🍺: `parsec`] <sup>💸♻️</sup>
- Install [Calcbot](https://apps.apple.com/us/app/calcbot-the-smart-calculator/id931657367?mt=12) <sup>🛄💰✨</sup>


## Install every brew package in one command
`$ brew install brave-browser 1password pastebot bartender warp iterm2 jetbrains-toolbox dotnet dotnet@6 pyenv nvm azure-data-studio azure-storage-explorer visual-studio-code postman gitkraken slack microsoft-teams telegram-desktop discord spotify spotmenu iina balenaetcher raspberry-pi-imager prusaslicer shapr3d parallels`

---
- 💰 - App has a one-time upfront purchase cost
- 💸 - App has a freemium pricing model with paid features
- ♻️ - App has a recurring subscription pricing model
- ✨ - Highly-recommended app or preference
- 🍺 - A homebrew package is available for this app
- 🛄 - App only available on the Mac App Store
- 🍎 - App only available on Apple Silicon Macs
