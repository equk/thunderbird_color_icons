# thunderbird_color_icons

override new mono icons with old color icons

## using userChrome

Place `userChrome.css` into `$profile/chrome` folder

### enable userChrome.css

`Settings/Options` > `Advanced` > `General` > `Config Editor...`
`toolkit.legacyUserProfileCustomizations.stylesheets` > `true`

### profile folder

Linux: `$HOME/.thunderbird/`

Windows: `%AppData%\Roaming\Thunderbird\Profiles\`

userChrome example in linux would be `$HOME/.thunderbird/xxxxxx.default/chrome/userChrome.css`