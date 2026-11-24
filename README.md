# SkeuoCord

SkeuoCord brings beveled toolbars, inset controls, square avatars, and blue accents to Discord. This fork updates Marda33’s original theme for the current desktop layout.

## Install on Equicord for Windows

1. Download [SkeuoCord.theme.css](https://raw.githubusercontent.com/coenflict/SkeuoCord/master/SkeuoCord.theme.css).
2. Place it in `%APPDATA%\Equicord\themes`. You can also open the folder from **User Settings → Themes → Local Themes**.
3. Enable **SkeuoCord** under **Local Themes**. If you already use the upstream theme, disable that copy before enabling this one.

The main stylesheet includes its artwork and defaults. Edit the variables near the top to customize avatar corners and borders, text shadows, and the window’s gradients.

## Compatibility

The desktop pass covers the title bar, server and DM sidebar, account controls, channel header, composer, menus, and settings tabs. The local smoke test used the installed Equicord theme loader with Discord’s Windows renderer and November 24, 2026 desktop styles. It exercised light, dark, darker, midnight, light with a dark sidebar, a custom gradient, and a narrow window using synthetic content.

The optional no-brand, horizontal server list, and classic title bar stylesheets use relative imports. To use them locally, keep their original filenames and copy the repository’s `updates` folder alongside the theme files. Enable the no-brand variant in place of the main entry. The horizontal list and title bar stylesheets are add-ons.

Some original replacement icons match Discord’s English labels. Other languages use the native icons in those positions.

## Original design

These previews are from [Marda33’s upstream SkeuoCord](https://github.com/marda33/skeuocord).

![Original SkeuoCord dark preview](Preview%20(Dark%20Theme).png)

![Original SkeuoCord light preview](Preview%20(Light%20Theme).png)
