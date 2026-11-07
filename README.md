# no-discord-titlebar-css
css snippet to remove the annoying discord titlebar because it looks stupid

before:
[![before](https://raw.githubusercontent.com/antoine-was-unavailable/no-discord-titlebar-css/refs/heads/main/media/before.png)](https://raw.githubusercontent.com/antoine-was-unavailable/no-discord-titlebar-css/refs/heads/main/media/before.png)

after:
[![before](https://raw.githubusercontent.com/antoine-was-unavailable/no-discord-titlebar-css/refs/heads/main/media/after.png)](https://raw.githubusercontent.com/antoine-was-unavailable/no-discord-titlebar-css/refs/heads/main/media/after.png)

put this into the QuickCSS on vesktop/vencord (or whatever you're using):
```css
.bar_c38106 {
    display: none;
}

:root {
    --custom-app-top-bar-height: 0px;
}

div.bar_3zSH5d
{
  display: none;
}

nav.wrapper_5dqHTG
{
  padding-top: 12px;
}
```
