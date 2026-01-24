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

div.c38106a3f0c3ca76-trailing
{
  display: none;
}

nav.wrapper_ef3116
{
  padding-top: 12px;
}
```
