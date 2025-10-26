# All Glass
# Systems 
## Windows
## Install:
[Rectify11](https://github.com/Rectify11/Installer)
And Install Mod: [MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone)



## Arch Linux KDE Plasma
## Install:
Kvantum Theme: [Flat Blur](https://www.pling.com/p/1326672/)
[ForceBlur](https://github.com/taj-ny/kwin-effects-forceblur) 

AutoScript:

# Apps
## Chromiums Browsers
In [Thorium]() Install: [ZenPlugin](https://github.com/weskerty/zeninternet-chromium)



## Firefox Browsers
Install: [ZenPlugin](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/)
Open `about:config`
Create and True flags:
```

```
Open File in FirefoxDATA/Profile/userChrome/.css
Paste:

```
@charset "UTF-8";
@-moz-document url(chrome://browser/content/browser.xhtml) {

    /* Transparencia completa del UI de Floorp / Firefox / Zen */

    :root {
        --tabpanel-background-color: transparent !important;
        background: transparent !important;
        --lwt-accent-color: transparent !important;
        --lwt-accent-color-inactive: transparent !important;
        --toolbar-bgcolor: transparent !important;
        --chrome-secondary-background-color: transparent !important;
        --chrome-background-color: transparent !important;
    }

    /* Ventana principal */
    #main-window,
    #browser,
    #appcontent,
    #tabbrowser-tabpanels,
    .browserStack,
    #tabbrowser-arrowscrollbox,
    #navigator-toolbox,
    #TabsToolbar,
    #nav-bar,
    #PersonalToolbar,
    #toolbar-menubar,
    .titlebar-color,
    #titlebar {
    background: transparent !important;
    background-color: transparent !important;
    border: none !important;
    }

    /* Evita que menús, popup panels, etc. pinten fondo sólido */
    menupopup,
    panel,
    #appMenu-popup,
    #context-navigation,
    #contentAreaContextMenu {
    background: transparent !important;
    -moz-appearance: none !important;
    color-scheme: light dark !important;
    }

    /* Quita color residual de bordes */
    #TabsToolbar::after,
    #nav-bar::after,
    #navigator-toolbox::after {
    background: transparent !important;
    border: none !important;
    }

    /* Pestaña activa: fondo más opaco */
    .tabbrowser-tab[selected="true"] .tab-background {
        background: rgba(30, 30, 30, 0.9) !important;
        backdrop-filter: blur(6px) !important;
        border-radius: 8px 8px 0 0 !important;
    }




}


```

In Zen: [Tutorial Here]()


## Telegram GlassTheme

https://github.com/user-attachments/assets/1c54be7c-960f-4494-b4ca-79b4bccc43de

OnlyWorkLinux.


## Android

[Resurection Remix Clear Redmi Note 8 [VBKwhXizKSA].webm](https://github.com/user-attachments/assets/b119f80c-9357-443d-917b-e651802a00b0)

[Substratum](https://play.google.com/store/apps/details?id=projekt.substratum.lite) 

Find and theme and rom work on 2025 😢
Or Edit apps [Team BlackOut](https://web.archive.org/web/20150212231255/http://www.designrifts.com/teamblackedoutapp/tutorials)



