cask_args appdir: '/Applications'

tap 'caskroom/cask'
tap 'caskroom/fonts'
tap 'homebrew/bundle'
tap 'homebrew/core'
tap 'homebrew/services'

brew 'curl'
brew 'htop'
brew 'git'
brew 'gradle'
brew 'gzip'
brew 'heroku'
brew 'mongodb', restart_service: true
brew 'nvm'
brew 'mas'
brew 'openssl'
brew 'python3'
brew 'ruby-build'
brew 'rbenv'
brew 'swiftlint'
brew 'vim'
brew 'wget'
brew 'yarn'
brew 'zsh'

cask 'appcleaner' unless system 'test -e /Applications/AppCleaner.app'
cask 'charles' unless system 'test -e /Applications/Charles.app'
cask 'gotomeeting'  unless system 'test -e /Applications/GoToMeeting.app'
cask 'iterm2'  unless system 'test -e /Applications/iTerm.app'
cask 'java' unless system '/usr/libexec/java_home --failfast'
cask 'kdiff3' unless system 'test -e /Applications/kdiff3.app'
cask 'paw' unless system 'test -e /Applications/Paw.app'
cask 'sketch' unless system 'test -e /Applications/Sketch.app'

cask 'font-roboto-mono'
cask 'font-source-code-pro'
cask 'font-inconsolata'

mas 'Twitter', id: 409789998 unless system 'test -e /Applications/Paw.app' 
mas 'iA Writer', id: 775737590  unless system 'test -e /Applications/iA\ Writer.app' 
