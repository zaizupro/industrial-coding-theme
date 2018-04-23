# industrial_coding

industrial_coding is a minimal dark Theme for Sublime Text 3. Also it is a syntax color scheme. The theme is based on the great theme [Afterglow](https://github.com/YabataDesign/afterglow-theme).

## Design & Colors
![sublime_theme_bleak](screenshots/sublime_theme_bleak.png)

![industrial_coding_normal](screenshots/normal.png)

![industrial_coding_bleak](screenshots/bleak.png)



---

<h6 align='center'><code>supa</code>bleak</h6>

![industrial_coding_supableak](screenshots/bleak.png)



## Installation


### Git Installation

Locate your Sublime Text 'Packages directory' by using the menu item 'Preferences -> Browse Packages...' .

Then, clone the repository using this command:

    git clone https://github.com/zaizupro/industrial-coding-theme.git


### Manual installation

* Download the [GitHub .zip](https://github.com/zaizupro/industrial-coding-theme/archive/master.zip)
* Unzip the files and rename the folder to 'industrial-coding-theme'.
* Find your 'Packages' directory using the menu item  'Preferences -> Browse Packages...'
* Copy the folder into your Sublime Text 'Packages' directory.


---

### Activation

###### Recommended

Open command palette via `Tools > Command Palette` (or <kbd>cmd/ctrl</kbd> + <kbd>shift</kbd> + <kbd>p</kbd>) and type `ict: Activate theme`.


###### Via Preferences

Activate this theme and color scheme by modifying your user preferences file, which you can find using the menu item 'Sublime Text -> Preferences -> Settings - User'.

Then add the following code settings. **(After activating the theme, you must restart Sublime Text.)**


**normal colors**
```json
{
    "theme": "industrial_coding.sublime-theme",
    "color_scheme": "Packages/industrial-coding-theme/industrial_coding_normal.tmTheme"
}
```

**bleak colors**
```json
{
    "theme": "industrial_coding.sublime-theme",
    "color_scheme": "Packages/industrial-coding-theme/industrial_coding_bleak.tmTheme"
}
```

For supableak theme:

```js
"theme": "industrial_coding.sublime-theme",
"color_scheme": "Packages/industrial-coding-theme/industrial_coding_supableak.tmTheme",
```

---

## Configuration
### Settings

```js
    "mouse_wheel_switches_tabs":    true, // comment

    "font_terminus":                true, // comment

    "highlight_modified_tabs":      true, // comment

    "show_tab_close_buttons":       true, // comment

    "bold_folder_labels":           true, // comment

    "sidebar_font_nobold":          true, // comment

    "statusbar_big_bold":           true, // comment

    "sidebar_no_icon":              true, // comment

    "folder_no_icon":               true, // comment
```
