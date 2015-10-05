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

## Markdown
https://guides.github.com/features/mastering-markdown/
## Git
git clone ssh://<server><absolute path>
### Cloning a repository via SSH
### Setup Git bare repository with FreeBSD
https://forums.freebsd.org/threads/how-to-setup-a-git-repository.10810/
## SSH
###Generating SSH keys
https://help.github.com/articles/generating-ssh-keys/
### Showing SHA256 hash/fingerprint for known_hosts file
ssh-keygen -l -E md5 -f ~/.ssh/known_hosts
### Showing old MD5 hash/fingerprint for known_hosts file
ssh-keygen -l -E md5 -f ~/.ssh/known_hosts
