# gitea-theme-github-dark

a gitea theme that looks like github-dark

## how to use

1. just copy `theme-ghdark.css` to

/path/to/gitea`/custom/public/css/theme-ghdark.css`

2. then modify 

/path/to/gitea`/custom/conf/app.ini`

```ini
[ui]
THEMES = auto,gitea,arc-green,ghdark ; <- Add "ghdark" here
DEFAULT_THEME = ghdark               ; <- and change the default theme
```

3. restart gitea and change your prefer theme to "ghdark"

4. enjoy!
