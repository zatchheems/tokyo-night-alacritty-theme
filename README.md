# Tokyo Night: Alacritty

### Alacritty theme based on VS Code and Vim themes

![alacritty-sample](https://user-images.githubusercontent.com/8506829/85086842-70e30a80-b1a1-11ea-9f69-0b12eb7b5f13.png)

Alacritty theme adapted from the excellent Tokyo Night VS Code theme.

Cobbles together pieces of [enkia/tokyo-night-vscode-theme](https://github.com/enkia/tokyo-night-vscode-theme)
and [ghifarit53/tokyonight-vim](https://github.com/ghifarit53/tokyonight-vim).

Pull requests welcome.

## Usage

Copy the contents of [tokyo-night.yaml](https://github.com/zatchheems/tokyo-night-alacritty-theme/blob/master/tokyo-night.yaml)
into `~/alacritty/alacritty.yml`, then set:

```yaml
# normal dark theme
colors: *tokyo-night

# "storm" uses a lighter BG color
colors: *tokyo-night-storm
```
