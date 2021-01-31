## Will this break my panel? (IMPORTANT)
This will not break your panel unless you use a diffrent theme version for a diffrent panel version, if it for some reason does break your panel it is simple to remove the theme.

## Panel Versioning
Make sure that the theme you are installing corresponds with the version of the panel you are running; no help will be given if you have mismatched versions!

How do i use them?
You simple follow the instructions below, mainly consisting of two or three changes you need to make before you build your panel.

## Install Theme
#User Side
Create a file called main.css in /var/www/pterodactyl/resources/scripts

In that file put this text

@import url(https://raw.githubusercontent.com/Lellee/Ptero-Themes-v1/master/latest/!!THEMENAME!!/user.css);
After that edit the file index.tsx in /var/www/pterodactyl/resources/scripts

On line 6 at the end of the imports add this

import './main.css';
After this build the panel, you can find information of how to do that here https://pterodox.com/customization/panel.html

After that just reload your panel and the theme is applied.

#Admin Side
In the file admin.blade.php in /var/www/pterodactyl/resources/views/layouts/

On line 36 put the text

<link rel="stylesheet" href="https://raw.githubusercontent.com/Lellee/Ptero-Themes-v1/master/latest/!!THEMENAME!!/admin.css">
After this build the panel, you can find information of how to do that here https://pterodox.com/customization/panel.html

After that just reload your panel and the theme is applied.

How do i use them?
You simple follow the instructions below, mainly consisting of two or three changes you need to make before you build your panel.


## Enola - 1.2.0, 1.2.1, and 1.2.2
Instructions to install the theme Enola are here
[Enola 1.2.2(Latest Panel Version)](https://github.com/Lellee/Ptero-Themes-v1/tree/master/latest/Enola)
![Preview](./preview/enola.png)


## Twilight - 1.1.3, 1.2.0, 1.2.1, 1.2.2
Instructions to install the theme Twilight are here
[Enola 1.2.2(Latest Panel Version)](https://github.com/Lellee/Ptero-Themes-v1/tree/master/latest/Twilight)
![Preview](./preview/twilight.png)

## Recolor - 1.2.0, 1.2.1, 1.2.2
This theme is a recolor of the panel that you can edit, more information here
[Recolor](https://github.com/Lellee/Ptero-Themes-v1/tree/master/latest/Recolor)

## Dracula - 1.2.0, 1.2.1, 1.2.2
This theme is a recolor of the panel that you can edit, more information here
[Dracula 1.2.2(Latest Panel Version)](https://github.com/Lellee/Ptero-Themes-v1/tree/master/latest/Dracula)
![Preview](./preview/Dracula.png)
![Preview](./preview/Dracula2.png)
## If you have suggestions or issues dm me on discord, Lellis#9405
