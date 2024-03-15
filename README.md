# gitea-theme-github-dark

This Gitea theme mimics the appearance of GitHub's dark theme for a familiar and visually pleasing experience.

## Preview

![图片](https://github.com/sb-child/gitea-theme-github-dark/assets/55868015/2dd4033f-ebcd-4fdf-af2f-fcd16cce3740)

## How to use

1. Copy the theme-ghdark.css file to /path/to/gitea/custom/public/assets/css/theme-ghdark.css.

2. Modify the Gitea configuration file located at /path/to/gitea/custom/conf/app.ini.

```ini
[ui]
THEMES = auto,gitea,arc-green,ghdark ; <- Add "ghdark" here
DEFAULT_THEME = ghdark               ; <- Change the default theme to "ghdark"
```

3. Restart Gitea.

4. Select the "ghdark" theme from your preferences.

5. Enjoy the GitHub-like experience!
