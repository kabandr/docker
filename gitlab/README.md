# Prerequisites
Docker is required. See the official installation documentation.

# Set up the volumes location
Before setting everything else, configure a new environment variable $GITLAB_HOME pointing to the directory where the configuration, logs, and data files will reside. Ensure that the directory exists and appropriate permission have been granted.

For Linux users, set the path to /srv/gitlab:
```
export GITLAB_HOME=/srv/gitlab
```
For macOS users, use the user’s $HOME/gitlab directory:
```
export GITLAB_HOME=$HOME/gitlab
```
The GITLAB_HOME environment variable should be appended to your shell’s profile so it is applied on all future terminal sessions:

Bash: `~/.bash_profile`
ZSH: `~/.zshrc`

The GitLab container uses host mounted volumes to store persistent data:

Local location		Container location	Usage
$GITLAB_HOME/data	/var/opt/gitlab		For storing application data.
$GITLAB_HOME/logs	/var/log/gitlab		For storing logs.
$GITLAB_HOME/config	/etc/gitlab		For storing the GitLab configuration files.

# Installation

Make sure you are in the same directory as docker-compose.yml and start GitLab:
```
docker compose up -d

```
