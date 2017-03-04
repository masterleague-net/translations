# MasterLeague.net translations

This repository contains user-contributed translations of MasterLeague.net.

## Repository structure

The file with strings used on the website in the source language (English) is called __django.po*t*__ (where *t* stands for template), and user-contributed translations (files called __django.po__) are located inside the **locale/xx/LC_MESSAGES** directories, where **xx** is the corresponding ISO 639-1 language code (e.g. **de** for German, **fr** for French, etc.):

```
locale
│
├── django.pot
├── de
│   └── LC_MESSAGES
│       └── django.po
├── ...
│
└── zh_Hant
    └── LC_MESSAGES
        └── django.po
```

## Improving an existing translation

To improve existing translations, you can use GitHub web interface to edit the files. Additionally, it is possible to edit the files using special translation software, which you can run locally on your computer (see the next section).

We recommend to install translation software, as it is much more convenient to use, but web interface is fine for small changes, like replacing one word with another.

1. Register an [new account on GitHub](https://github.com/join)
2. Open the translation file that you would like to edit, e.g. the [German](locale/de/LC_MESSAGES/django.po) one
3. Follow the steps described [on this help page](https://help.github.com/articles/editing-files-in-another-user-s-repository/) to make and submit the edits
4. We will be notified about your changes & will review / deploy them to the website

## Contributing a new translation

If you want to contribute a brand new translation, follow the steps below:

1. Download and install free [Poedit](https://poedit.net) translation software
2. Download [django.pot](https://raw.githubusercontent.com/masterleague-net/translations/master/locale/django.pot) source file by right clicking on this link and choosing "Save Link As..."
3. Create a new translation and save it on your hard drive as *django.po* (check [this guide](https://www.orange-themes.com/how-to-translate-website-with-poedit/) explaning how!)
4. Upload this file [using GitHub interface](https://help.github.com/articles/adding-a-file-to-a-repository/) (preferred) or send it to abathur@masterleague.net

Be sure to let us know if (and how) you would like to appear on our [Credits](https://masterleague.net/credits/) page!
