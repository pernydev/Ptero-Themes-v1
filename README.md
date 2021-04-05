## Install Help

## User Panel

Create a file in `/var/www/pterodactyl/resources/scripts` called `main.css`

In `main.css` put ```@import url(https://lellee.github.io/Ptero-Themes-v1/latest/!!THEMENAME!!/user.css);```
`!!THEMENAME!! replace with example, Dracula`

Edit `/var/www/pterodactyl/resources/scripts/index.tsx` add ```import './main.css';``` at line 6

## Admin panel

Edit `admin.blade.php` in `/var/www/pterodactyl/resources/views/layouts/`

Go to line 36 and put ```@import url(https://lellee.github.io/Ptero-Themes-v1/latest/!!THEMENAME!!/admin.css);```
`!!THEMENAME!! replace with example, Dracula`

## Rebuild panel !!ONLY UBUNTU!!

Install NodeJS `curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash - && apt install -y nodejs`

Install Yarn Dependencies `npm i -g yarn`

Run `node -v` make sure it say 12.x.x or newer

Steps after tihs message, Make sure you are in `/var/www/pterodactyl`

Install Panel Dependencies `yarn install && yarn add @emotion/react`

Build `yarn build:production`

## Help

Contact `Lellis#9405`


## Previews 1.1.x - 1.3.x

## Enola - 1.1.x - 1.3.x
Instructions to install the theme Enola are here
[Enola 1.2.2(Latest Panel Version)](https://github.com/Lellee/Ptero-Themes-v1/tree/master/latest/Enola)
![Preview](./preview/enola.png)

## Twilight - 1.1.x - 1.3.x
Instructions to install the theme Twilight are here
[Enola 1.2.2(Latest Panel Version)](https://github.com/Lellee/Ptero-Themes-v1/tree/master/latest/Twilight)
![Preview](./preview/twilight.png)

## Recolor - 1.1.x - 1.3.x
This theme is a recolor of the panel that you can edit, more information here
[Recolor](https://github.com/Lellee/Ptero-Themes-v1/tree/master/latest/Recolor)

## Dracula - 1.1.x - 1.3.x
This theme is a recolor of the panel that you can edit, more information here
[Dracula 1.2.2(Latest Panel Version)](https://github.com/Lellee/Ptero-Themes-v1/tree/master/latest/Dracula)
![Preview](./preview/Dracula2.png)
