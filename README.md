<div align="center">
    <h1>
        <img alt="BIBLIOLITE - INTEGRATED LIBRARY SYSTEM" src="cover.svg" height="150"/>
    </h1>
    <p>
        <a href="https://codeigniter.com/" target="_blank">
            <img alt="Made with CodeIgniter" src="https://img.shields.io/badge/Made_with-CodeIgniter-EE4623.svg?longCache=true&style=for-the-badge&logo=codeigniter"/>
        </a>
        <a href="https://bibliolite.herokuapp.com" target="_blank">
            <img alt="See It In Action" src="https://img.shields.io/badge/See_It_In_Action-@Heroku-512DA8.svg?longCache=true&style=for-the-badge&logo=heroku"/>
        </a>
    </p>
</div>

Built using **[CodeIgniter Framework](https://codeigniter.com)**. The system uses **[ModularAdmin Bootstrap Framework](https://github.com/modularcode/modular-admin-html)** in its design, layout, and components. This allows screen-size responsiveness, and user-friendly interface. BiblioLite contains all necessary modules of a basic ILS, cataloging and circulation, with AutoCatalog support from Google Books and OCLC Classify.

----

## Features

* **Search and Retrieval** - Enhanced searching mechanisms for various fields. Selective / advanced search feature enabled.
* **Cataloging** - Intermediate bibliographic description (title statement of resposibility, headings, publication, series, classification, and holdings). Additional fields to follow on next updates. With **AutoCat** - retrieving bibliographic data from Google Books and OCLC, plus a Cutter number generation engine.
* **Circulation / Lending** - Integrated cart module for multiple checkouts. Easy interface.
* **User Management** - Manage staff accounts with different roles and privileges. Client / Guest account not yet supported.
* **Theming and Customization** - ModularAdmin theme supports six base colors (blue, red, green, seagreen, purple, and orange). Custom logo and banner supported. Photo upload with crop tool.

### See It In Action

* Go to: **<https://bibliolite.herokuapp.com/>** (Hosted at Heroku)
    - Username: **`sysadmin`**
    - Password: **`password`**

## Limitations

* MARC and MARC XML is not **yet** supported.
* Adding electronic material links is not **yet** supported.
* AutoCat sources are limited to OLC Classify and Google Books due to pending API access requests from other sources.

## Requirements

* **PHP Version** - At least **5.6.0** tested and built using version 7.1 (recommended).
* **PHP Extensions** - mysqli, curl
* **MySQL Version** - **5.0.12** (recommended). Tested and built using MariaDB 10.1.20
* **Web Server** - **Apache 2.4**. May work on lighttpd, but will have to setup url-rewrite.
     
----

This work is licensed under a **[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)**.

Copyright (c) 2019 **[Gerard Balaoro](mailto:gmbalaoro@outlook.com)**
