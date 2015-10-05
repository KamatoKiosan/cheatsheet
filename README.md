# A cheat sheet
## KDE
* Switch to first session: ctrl+alt+f7
* Switch to second session: ctrl+alt+f8

## i3
* Reference card: http://i3wm.org/docs/refcard.html
* Basics
  * Open a new terminal: mod+enter
  * Focus left: mod+h
  * Focus down: mod+j
  * Focus up: mod+k
  * Focus left: mod+l
  * Toggle focus mode: mod+space
* Moving windows
  * Move window left: mod+shift+h
  * Move window down: mod+shift+j
  * Move window up: mod+shift+k
  * Move window right: mod+shift+l
* Modifying windows
  * Toggle fullscreen: mod+f
  * Split in vertical orientation: mod+v
  * Split in horizontal orientation: mod+g
  * Enter resize mode: mod+r
  * Leave resize mode: enter | esc
* Changing container layout
  * Change container layout to toggle split: mod+e
  * Change container layout to stacking: mod+s
  * Change container layout to tabbed: mod+w
* Floating
  * Toggle tiling / floating: mod+shift+space
* Using workspaces
  * Switch to workspace #: mod+#
  * Move a window to another workspace: mod+shift+number
* Opening applications
  * Open dmenu: mod+d
  * Kill a window: mod+shift+q
* Restart / Exit
  * Reload the configuration file: mod+shift+c
  * Restart i3 inplace: mod+shift+r
  * Exit i3: mod+shift+e
* Other
  * Focus the parent container: mod+a
  * Focus the child container: mod+d
  * Move focused container to workspace #: mod+shift+h

## Vimperator / Firefox
* Open new webpage: :open https://webpage.com
* Open a new webpage in tab: :tabopen https://webpage.com
* Open next page by incrementing URL number: ctrl+a
* Open next page by decrementing URL number: ctrl+x
* Go up to parent directory: gu
* Go back in history: :back
* Go forward in history: :forward
* Open a link in current window: f then enter number
* Open a link in new tab: F then enter number
* Enter pass-through mode: ctrl+z

## Markdown
https://guides.github.com/features/mastering-markdown/
## Git
### Cloning a repository via SSH
`git clone ssh://<server><absolute path>`
### Setup Git bare repository with FreeBSD
https://forums.freebsd.org/threads/how-to-setup-a-git-repository.10810/
## SSH
###Generating SSH keys
https://help.github.com/articles/generating-ssh-keys/
### Showing SHA256 hash/fingerprint for known_hosts file
ssh-keygen -l -E md5 -f ~/.ssh/known_hosts
### Showing old MD5 hash/fingerprint for known_hosts file
ssh-keygen -l -E md5 -f ~/.ssh/known_hosts
## Fish
* bash/fish translation table: https://en.wikipedia.org/wiki/Friendly_interactive_shell#bash.2Ffish_Translation_table
* oh-my-fish Git repository: https://bpinto.github.io/oh-my-fish/
* oh-my-fish command: omf
## XTerm
* Activate changes in .Xresources: xrdb ~/.Xresources
## Fonts
* Show available fonts: `fc-list | cut -f2 -d: | sort -u`
