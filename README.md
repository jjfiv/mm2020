# mm2020
Git workshop scratch space: a robot is running to add commits every time you change.

# How does the robot work?

``update.sh`` gets run with fairly high frequency; it runs a Python script ``update.py`` to check for changes to the git repo and then runs a series of commands if upstream changes are found!
