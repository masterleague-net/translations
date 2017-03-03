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
