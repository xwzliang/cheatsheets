# error enospc: system limit for number of file watchers reached vscode
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
