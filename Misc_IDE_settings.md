# Misc IDE Settings

## Python linter flake8 config

`tox.ini`

```ini
[flake8]
# E501 is line length
# E722 is only having an generic except
# F401 is unused imports
# F403 is star import
# F405 using stuff from star import
ignore = E501, E722, F401, F403, F405
```

## VS Code launch.json

- add `"cwd": "${fileDirname}"` to the generic launch.json so the working directory when running the file is the directory the file is in.
