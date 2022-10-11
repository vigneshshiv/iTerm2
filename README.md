# Spice up your MacOS Terminal with iTerm2

### Step 1: Install Homebrew

Run: /bin/bash -c -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### Step 2: Install iTerm2

Run: brew install --cask iterm2

### Step 3: Install Git

Run: brew install git

### Step 4: Install oh-my-zsh

Run: sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

### Step 5: Install fonts

_Download & Install_: https://github.com/vigneshshiv/iTerm2/SourceCodePro%2BPowerline%2BAwesome%2BRegular.ttf

### Step 6: Install Theme

Run: git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

Set theme on .zshrc: ZSH_THEME="powerlevel10k/powerlevel10k"

### Step 7: Install custom iTerm2 colors

Copy: https://raw.githubusercontent.com/vigneshshiv/iTerm2/vigneshshiv.itermcolors

Paste contents in a new file somewhere and name it _filename.itermcolors_

### Step 8: Update iTerm2 preferences

Create new profile, make it default, delete default profile

Set colors to newly created itermcolors files

Set font to SourceCode+PowerLine+AwesomeRegular

### Step 9: Configure Power Level 10K

Re-launch iTerm2 and follow prompts

### Step 10: Enable suggestions

_Clone_: git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

Add plugin to .zshrc file: plugins=(zsh-autosuggestions)

### Step 11: Configure VS Code

Update terminal.integrated.fontFamily setting to 'SourceCodePro+PowerLine+AwesomeRegular'

### Step 12: Enable quake-style terminal

Open iterm2 preferences > keys, then configure hotkey to Ctrl + ~ to Show/Hide all windows with a system-wide hotkey

Open iterm2 preferences > profile > window, set space to all spaces and check hide after opening

Open system preferences > users & groups > login items, then add iterm. Check hide.
