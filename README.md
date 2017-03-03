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

1. Register an [new account on GitHub](https://github.com/join)
2. Open the translation file that you would like to edit, e.g. the [German](locale/de/LC_MESSAGES/django.po) one
3. Follow the steps described [on this help page](https://help.github.com/articles/editing-files-in-another-user-s-repository/) to make and submit the edits
4. We will be notified about your changes & will review / deploy them to the website
