# gitea-theme-github-dark

a gitea theme that looks like github-dark

## preview

![图片](https://user-images.githubusercontent.com/55868015/206542054-321b6c3f-3068-4d87-9655-6ee0763db9f4.png)

Just for css preview, dom tree was modified.

## how to use

1. just copy `theme-ghdark.css` to

/path/to/gitea/`custom/public/assets/css/theme-ghdark.css`

2. then modify 

/path/to/gitea/`custom/conf/app.ini`

```ini
[ui]
THEMES = auto,gitea,arc-green,ghdark ; <- Add "ghdark" here
DEFAULT_THEME = ghdark               ; <- and change the default theme
```

3. restart gitea and change your prefer theme to "ghdark"

4. enjoy!
