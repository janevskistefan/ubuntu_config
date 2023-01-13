# Permanent path

From <a href="https://userbase.kde.org/Session_Environment_Variables/en">session-environment-variables</a>:

```
It is simple to set environment variables that affect your whole session. Plasma will execute any script it finds in $HOME/.config/plasma-workspace/env whose filename ends in .sh, and it will maintain all the environment variables set by them. It is important that any variable you want to set must be also exported. In the case of PATH, for instance, your system will be set up with certain likely directories as the likely places to find things.
```
- Creating a symbolic (soft) link to the required location that points to `path.sh`:
```
ln -s path.sh $HOME/.config/plasma-workspace/env/path.sh
```
