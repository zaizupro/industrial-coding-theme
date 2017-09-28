# industrial_coding

industrial_coding is a minimal dark Theme for Sublime Text 3. Also it is a syntax color scheme. The theme is based on the great theme [Afterglow](https://github.com/YabataDesign/afterglow-theme).

## Design & Colors

![industrial_coding_normal](screenshots/normal.png)

![industrial_coding_bleak](screenshots/bleak.png)

## Installation


### Git Installation

Locate your Sublime Text 'Packages directory' by using the menu item 'Preferences -> Browse Packages...' .

Then, clone the repository using this command:

    git clone https://github.com/zaizupro/industrial-coding-theme.git "Theme - industrial_coding"


### Manual installation

* Download the [GitHub .zip](https://github.com/zaizupro/industrial-coding-theme/archive/master.zip)
* Unzip the files and rename the folder to 'Theme - industrial_coding'.
* Find your 'Packages' directory using the menu item  'Preferences -> Browse Packages...'
* Copy the folder into your Sublime Text 'Packages' directory.


## Activating the Theme

Activate this theme and color scheme by modifying your user preferences file, which you can find using the menu item 'Sublime Text -> Preferences -> Settings - User'.

Then add the following code settings. **(After activating the theme, you must restart Sublime Text.)**


**normal colors**
```json
{
    "theme": "industrial_coding.sublime-theme",
    "color_scheme": "Packages/Theme - industrial_coding/industrial_coding_normal.tmTheme"
}
```

**bleak colors**
```json
{
    "theme": "industrial_coding.sublime-theme",
    "color_scheme": "Packages/Theme - industrial_coding/industrial_coding_bleak.tmTheme"
}
```


## Configuration

    "mouse_wheel_switches_tabs"
    
    "font_terminus"

    "highlight_modified_tabs"

    "show_tab_close_buttons"

    "bold_folder_labels"

    "sidebar_font_nobold"

    "statusbar_big_bold"

	"sidebar_no_icon"

	"folder_no_icon"