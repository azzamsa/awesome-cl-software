<div align="center">
<h1>Awesome Common Lisp Application Software</h1>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

![Lisp logo](https://github.com/azzamsa/lisp-logo/blob/master/logos/lisp-lizard-with-text.svg)
    
</div>

---

This is a list of awesome [application software](https://en.wikipedia.org/wiki/Application_software) built with Common Lisp.

We want to keep the 'master' list curated. If you want to uncurated list, see [complete list branch](https://github.com/azzamsa/awesome-cl-software/tree/complete-list).

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [Awesome Common Lisp Application Software](#awesome-common-lisp-application-software)
    - [Applications](#applications)
        - [Audio](#audio)
        - [Blogging](#blogging)
            - [Static Blog Generator](#static-blog-generator)
        - [Chat](#chat)
            - [Chat Bot](#chat-bot)
        - [Development Tools](#development-tools)
            - [Databases](#databases)
            - [IDE](#ide)
            - [Others](#others)
        - [Desktop Environment](#desktop-environment)
        - [Editors](#editors)
        - [Education](#education)
        - [File Manager](#file-manager)
        - [Games](#games)
        - [Graphics](#graphics)
            - [Image Creation](#image-creation)
            - [Image Viewer](#image-viewer)
        - [Internet](#internet)
            - [Browser](#browser)
            - [Torrent](#torrent)
            - [RSS](#rss)
        - [Operating System](#operating-system)
        - [Productivity](#productivity)
        - [Publishing](#publishing)
        - [Social news](#social-news)
        - [Utilities](#utilities)
        - [Video Player](#video-player)
        - [Wiki software](#wiki-software)
        - [Window Manager](#window-manager)
        - [Other](#other)
            - [Historical Purposes](#historical-purposes)
    - [Mobile Applications](#mobile-applications)
    - [Other Lists](#other-lists)
    - [Contributors](#contributors)
    - [Guidelines to contribute](#guidelines-to-contribute)
    - [Unsure how to contribute?](#unsure-how-to-contribute)
    - [Note](#note)
    - [License](#license)

<!-- markdown-toc end -->


## Applications

### Audio

- [OpusModus](http://opusmodus.com/) - a comprehensive computer-aided environment for the whole work of music composition. [Proprietary].
- [OM7](https://github.com/openmusic-project/om7) - a new implementation of the OpenMusic visual programming and computer-aided composition environment including a number of improvements on graphical interface, computational mode, and connection to external software libraries. [GPL3][2].
- [Common Music](https://github.com/ormf/cm) - the repository of an ancient version of Common Music (version 2.12.0), the presumably last version which ran on Common Lisp dating from around 2007-09, before work on Common Music shifted to (scheme-based) cm3.
- [Incudine](https://github.com/titola/incudine) -  Music/DSP programming environment for Common Lisp. Useful to design software synthesizers or sound plugins from scratch. It is also a compositional tool that allows to produce high quality sounds controllable at the sample level, defining and redefining the digital signal processors and the musical structures on-the-fly.
- [Shuffletron](https://github.com/ahefner/shuffletron) - a search-based music player for the terminal. MIT-style licence.
- [Ernestine](https://github.com/nlamirault/ernestine) - Ernestine is a music management application in McClim. [MIT].
- [CLM](https://ccrma.stanford.edu/software/clm/) - Common Lisp Music is a music synthesis and signal processing package in the Music V family. It provides much the same functionality as Stk, Csound, SuperCollider, PD, CMix, cmusic, and Arctic — a collection of functions that create and manipulate sounds, aimed primarily at composers (in CLM's case anyway).
- [Open Music](https://github.com/openmusic-project/OM6) - a visual programming, computer-aided composition environment. [GPL3][2].
- [PWGL](http://www2.siba.fi/PWGL/) - A Visual Programming Language for Music and Sound.
- [ScoreCloud](https://scorecloud.com/) - A web and mobile application to automatically create music notation from music performance or recordings. Built with LispWorks.

### Blogging

- [Cliki2](https://github.com/vsedach/cliki2) - The wiki software behind cliki.net [AGPL3]
- [Ext-blog](https://github.com/kevinlynx/ext-blog) - blog engine. It supports custom theme and you can port a WordPress theme for it. [No License Specified].

#### Static Blog Generator

- [Coleslaw](https://github.com/kingcons/coleslaw) - Flexible Lisp Blogware.

### Chat

- [Lisp-chat](https://github.com/ryukinix/lisp-chat) - An experimental minimal chat. [MIT].
- [Potato](https://github.com/cicakhq/potato) - Delicious conversations platform in Common Lisp and ClojureScript.
- [Collen](https://github.com/Shinmera/colleen) - Common Lisp IRC bot with a modular framework.
- [Lichat](https://shirakumo.github.io/maiden/clients/lichat/) - Lichat client for Maiden. [Artistic License 2.0]

#### Chat Bot

- [Lisp-paste](https://github.com/stassats/lisp-bots) - Bots from #lisp. [MIT].
- [Alice](https://github.com/TeMPOraL/alice) - Alice Margatroid, a dollmaster that pretends not to be a doll itself. [No license Specified].
- [Magitek](https://github.com/sjl/magitek) - Whimsical robots infused with just a hint of magic. No license specified.

### Development Tools

- [Cepl](https://github.com/cbaggers/cepl) - Code Evaluate Play Loop. [2-clause BSD].
- [Quickutil](https://github.com/tarballs-are-good/quickutil) - The solution to the Utility Library problem. [No License Specified].
- [Quickdocs](https://github.com/quickdocs/quickdocs) - Ready and Up-to-Date Documentation for All Common Lisp Projects. [No License Specified].
- [Lake](https://github.com/takagi/lake) - Lake is a GNU make like build utility in Common Lisp. [MIT].
- [Asdf-viz](https://github.com/guicho271828/asdf-viz) - ASDF system dependency visualizer. [LLGPL].
- [Cl-bunny](https://github.com/cl-rabbit/cl-bunny) - Common Lisp RabbitMQ client based on IOLib.
- [Eazy-project](https://github.com/guicho271828/eazy-project) -  Interactive Project Generator & Manager. [No License Specified].
- [barf](https://github.com/ebzzry/barf) - A simple Nixpkgs and NixOS helper. [CC0].
- [Seed](https://github.com/phantomics/seed) - Interactive software environment based on Common Lisp. [GPL3].
- [Sluglisp](https://github.com/ahungry/sluglisp) - Like Quicklisp, only slower (a web GUI based Quicklisp for searching the projects). [No License Specified].
- [prometheus.cl](https://github.com/deadtrickster/prometheus.cl) - Prometheus.io Common Lisp client. [MIT].


#### Databases

- [Pgloader](https://github.com/dimitri/pgloader/) - Migrate to PostgreSQL in a single command!. [PostgreSQL License]
- [Pgchart](https://github.com/dimitri/pgcharts) - A self-contained web application that takes as input an SQL query text and outputs its data as a chart. [No License Specified]
- [LambdaLite](https://github.com/Wukix/LambdaLite) - A functional, relational database in about 250 lines of Common Lisp. [MIT].
- [AllegroGraph](https://franz.com/agraph/allegrograph/) - A modern, high-performance, persistent graph database.

#### IDE

- [SLIME](https://github.com/slime/slime) - The Superior Lisp Interaction Mode for Emacs.
- [Sly](https://github.com/joaotavora/sly) - Sylvester the Cat's Common Lisp IDE (slime's fork)

For more, see [Awesome-cl](https://github.com/CodyReichert/awesome-cl).

#### Others

- [Regex-coach](http://weitz.de/regex-coach/) - a graphical application for Windows which can be used to experiment with (Perl-compatible) regular expressions interactively. Freeware.

### Desktop Environment

- [Mcclim-desktop](https://github.com/gas2serra/mcclim-desktop) - a clim-desktop clone. [GPL3].

### Editors

- [Lem](https://github.com/cxxxr/lem) - Common Lisp editor/IDE with high expansibility. [MIT].
- [Second Climacs](https://github.com/robert-strandh/Second-Climacs) - Version 2 of the Climacs text editor.
- [MarkEdit](https://github.com/ceramic/markedit/) - Markdown editor and previewer built with Ceramic. [No license specified].
- [Med](https://github.com/burtonsamograd/med) - Emacs-like text editor for the Mezzano operating system. [MIT].
- [Hemlock](https://github.com/bluelisp/hemlock) -  Portable version of the Hemlock editor. [No Licence Specified].

### Education

- [ACL2](https://github.com/acl2/acl2) - A theorem proving environment. [3-clause BSD].
- [Axiom](https://github.com/daly/axiom) -  Axiom is a free, open source computer algebra system.
- [Biochat](https://github.com/Bohdan-Khomtchouk/Biochat) - Where biological datasets learn to talk to each other. [MIT].
- [Maxima](https://sourceforge.net/projects/maxima/files/) - Computer Algebra System written in Common Lisp. [GPL2].
- [PVS](https://github.com/SRI-CSL/PVS) - The People's Verification System . [GPL2].
- [Geiriadur](http://www.cymraeg.ru/geiriadur/disgrifiad-2.html) - Dictionary lookup engine and a dictionary editing system. [No license specified].
- [Sparser](https://github.com/ddmcdonald/sparser) - A natural language understanding system for English, [No license specified].
- [Weyl](https://github.com/OdonataResearchLLC/weyl) - Computer algebra substrate from Cornell University. [No license specified].

### File Manager

- [Filer](https://github.com/froggey/Mezzano) - Mezzano File Manager.

### Games

- [sucle](https://github.com/terminal625/sucle) - A Minecraft clone (voxel game engine). [MIT].
- [CotD](https://github.com/gwathlobal/CotD) - A roguelike battle of Angels and Demons in the streets of a Human city. [GPL3].
- [Jak and Daxter](https://en.wikipedia.org/wiki/Jak_and_Daxter) - Jak and Daxter. [Proprietary].
- [Option-9](https://github.com/psilord/option-9) -  A Shoot'em Up Game. No license specified.
- [Asteroids](https://github.com/andyhd/asteroids) - Asteroids game in Common Lisp. [No License Specified].
- [Cl-dino](https://github.com/VitoVan/cl-dino) - A Chrome Dinosaur Robot. [GPL3].
- [Perfectstorm](https://github.com/lispgames/perfectstorm) - Perfectstorm is a real time strategy game study. [MIT](https://opensource.org/licenses/MIT).
- [Notalone](https://github.com/borodust/notalone) - You wake up nowhere in the night. Hungry zombies around, but your ol' pal "BOOMSTICK" is with you. [GPL3]
- [Starwar](https://github.com/xzpeter/starwar) - Starwar. [No License Specified].
- [The-invaders](https://github.com/sebity/the-invaders) - A remake of the classic game Space Invader. [GPL2].
- [Ninja-sphere](https://github.com/rpav/ninja-sphere) - Ninja Sphere. No license specified.


### Graphics

#### Image Creation

- [Sketch](https://github.com/vydd/sketch) -A Common Lisp framework for the creation of electronic art, visual design, game prototyping, game making, computer graphics, exploration of human-computer interaction, and more.
- [Snek](https://github.com/inconvergent/snek) - An experimental system for writing generative systems.
- [Parasol](https://github.com/Shinmera/parasol) - A Common Lisp painting application.
- [Wigflip](http://wigflip.com/) - image playground.
- [PTC's 3d designer](https://www.ptc.com/en/products/cad/3d-design) - 3D Design Software. [Proprietary].
- [Mirai](http://www.izware.com/mirai) - 3D editor built on the winged-edge data structure. [Proprietary].
- [Flow](https://github.com/Shinmera/flow) - Tools for the representation of graphs and flowcharts.
- [McPixel](https://github.com/ahefner/McPixel) - A toy Lisp program for drawing and animating pixel art.  No license specified.
- [Stektcheroo](https://github.com/xach/sketcheroo) - 2D drawing and layout.


#### Image Viewer

- [Halftone](https://github.com/Shinmera/halftone) - A simple image viewer in Common Lisp.
- [Spectacle](https://github.com/slyrus/spectacle) - A CLIM application for viewing opticl images. [2-clause BSD](https://directory.fsf.org/wiki/License:BSD_2Clause).

### Internet

#### Browser

- [Nyxt](https://github.com/atlas-engineer/nyxt) - The Internet on your terms. A keyboard-driven web browser designed for power users.
- [Lispkit](https://github.com/AeroNotix/lispkit) - A lisp web browser using WebKit 

#### Torrent

- [cl-torrents](https://github.com/vindarel/cl-torrents) - a library and app with a command line and readline interface to search for torrents on popular trackers.

#### RSS

- [rssparser](https://bitbucket.org/tux_/rssparser.lisp) - A Web-to-RSS parser in Common Lisp for websites that don't have RSS feeds.

### Operating System

- [Mezzano](https://github.com/froggey/Mezzano) - An operating system written in Common Lisp
- [Yalo](https://github.com/whily/yalo) - Lisp OS running on bare metal x86-64 hardware (WIP) 


### Productivity

- [Grammarly](https://www.grammarly.com/) - Grammar checking. [Proprietary].
- [Turtl](https://github.com/turtl/api) - a secure note taking, bookmarking and document storage app. [AGPL].
- [Deftask](https://deftask.com/) - Painless task management for teams. [Partly Open Source].
- [Ichiran](https://github.com/tshatrov/ichiran) - Linguistic tools for texts in Japanese language. [MIT].
- [Projectured](https://github.com/projectured/projectured) -  ProjecturEd is a generic purpose projectional editor. [No License Specified].

### Publishing

- [ABStock](https://github.com/vindarel/ABStock) - allows to publish an online catalogue of products. Primarily made for books.


### Social news

- [Reddit v1 source code](https://github.com/tamurashingo/reddit1.0/) ([reddit](https://www.reddit.com/r/programming/comments/883vzs/old_reddit_source_code/)). [Proprietary].

### Utilities

- [cl-ledger](https://github.com/ledger/cl-ledger) - a port of the double-entry accounting system. [3-clause BSD].
- [Mediaimport](https://github.com/fourier/mediaimport) - Import media files (jpgs/movies) from cameras. [No License Specified].
- [Hju](https://github.com/TeMPOraL/hju) -  Simple command line (CLI) controller for Hue lights. [MIT].


### Video Player

- [Terentino](https://github.com/froggey/Mezzano) - Mezzano Video Player. [MIT].

### Wiki software

- [Aliw](https://github.com/vy/aliw) - A Lisp in Wonderland (aka. ALIW) is a wiki software. [2-clause BSD].

### Window Manager

- [Stumpwm](https://github.com/stumpwm/stumpwm) - The Stump Window Manager.
- [Paulownia](https://github.com/stumpwm/paulownia) - A modern re-write of stumpwm. [GPL2].

### Other

- [Pocket Change](https://www.pocket-change.jp/en/) - Converts leftover coins and bills to electronic money, gift codes, and coupons of your choice. [Proprietary].
- [Kindista](https://github.com/kindista/kindista) - A social network for local sharing. [AGPL3]
- [Cyc](http://www.cyc.com/) - Build a database of heuristics. [Proprietary].
- [Denso](https://github.com/start-jsk/denso) - A controller package suite for robots from Densowave based on open-industrial-ros-controllers. [No License Specified].
- [Matrix Airfare Search](http://matrix.itasoftware.com/) - low-fare search engine. [Proprietary].
- [Missile Defense](http://www.raytheon.com/) - Missile Defense at Raytheon. [Proprietary].
- [Orbitz](https://www.orbitz.com/) -  Travel fare aggregator website and travel metasearch engine. [Proprietary].
- [Piano](http://www.lissys.demon.co.uk/) - A complete aircraft analysis suite. [Proprietary].
- [Routific](https://routific.com/) - Route optimization and fleet management. [Proprietary].
- [Zen](https://github.com/pyb/zen) - The zen X server in Common Lisp. [GPL3].

#### Historical Purposes

- [DART](https://en.wikipedia.org/wiki/Dynamic_Analysis_and_Replanning_Tool) - Application to optimize and schedule the transportation of supplies or personnel and solve other logistical problems.
- [ICAD](https://en.wikipedia.org/wiki/ICAD_(software)) - A knowledge-based CAD system.
- [Interleaf Publisher](https://en.wikipedia.org/wiki/Interleaf) - A document processor.
- [Itasca database][Expat] - Database.
- [Metal](https://en.wikipedia.org/wiki/METAL_MT) - Siemens machine translation system.
- [Sk8](https://en.wikipedia.org/wiki/SK8) - A multimedia authoring environment.
- [Action!][Expat] - Expertelligence' Interface Designer.
- [PRISM](http://www.radonc.washington.edu/medinfo/prism/) - The Prism project is a long term project to build software tools for radiation therapy planning, including artificial intelligence tools as well as manual simulation systems.
- Endless list. See [complete list branch](https://github.com/azzamsa/awesome-cl-software/tree/complete-list).


## Mobile Applications

- [ScoreCloud Express](https://apps.apple.com/us/app/scorecloud-express/id566535238) - An iPhone and iPad application that automatically creates music notation from music performance or recordings.
- [CL REPLay](https://gitlab.com/eql/EQL5-Android/tree/master/examples/REPL) - A REPL with simple editor. No license specified.
- [Sokoban](https://gitlab.com/eql/EQL5-Android/tree/master/examples/sokoban) - Sokoban game. No license specified.



## Other Lists

- [Allegro Common Lisp Success Stories ](https://franz.com/success/) - by Franc Inc
  - [Customer Application List](https://franz.com/success/all_customer_apps.lhtml)
- [awesome-cl](https://github.com/CodyReichert/awesome-cl)
- [Awesome Lisp Company](https://github.com/azzamsa/awesome-lisp-companies)
- [Cliki](http://cliki.net/) -  CLiki the common lisp wiki
  - [Application](http://cliki.net/application) - Stand-alone applications written in Common Lisp
- [Common Lisp games](https://github.com/lispgames/lispgames.github.io/wiki/Common-Lisp)
  - [Lisp Game Jams](https://github.com/lispgames/lispgames.github.io/wiki/Lisp-Game-Jams)
- [Lisp Companies](http://pchristensen.com/blog/lisp-companies/) - by Peter Christensen.
- [Lisp-lang Success Stories](http://lisp-lang.org/success/)
- [LispWorks Success Stories  ](http://www.lispworks.com/success-stories/index.html)
- [Paul Graham - Applications](http://www.paulgraham.com/apps.html)
- [Wikipedia Common Lisp Software](https://en.wikipedia.org/wiki/Category:Common_Lisp_software)



## Contributors

Thanks to All of Github contributors and Everyone @ reddit.com/r/lisp ad r/Common_Lisp/ for many suggestions and compliments.

## Guidelines to contribute

Please follow this format of the list  `[Appname](#link) - description. [License].`
if you want to make a contribution.

- Put the name of the **application** and **link** to its **homepage** in the list.
- Write a **short description** for the application.
- Add a **license** in the end of the list. *see the list format above*
- Make sure it is put under the **appropriate topic**.
- If the application doesn't fit in any **existing topic**, make a **new one** for it.
- Sort the item by its **popularity**.
  - we come up with this approach since alphabetically sorted make people unnoticed which app has more active development and which app unmaintained or abandoned.

## Unsure how to contribute?

- [How to Use Github](https://guides.github.com/activities/forking/)
- [How to Git from the Command Line](https://rogerdudler.github.io/git-guide/)
- [What is Markdown?](https://github.com/LewisVo/Markdown-Tutorial) - Markdown is the writing method used to create this list, if you want to know how to format properly, it's best that you learn how to use Github Markdown.
- [Alternative Markdown Guide:](https://guides.github.com/features/mastering-markdown/)

## Note

- You can learn about licenses in [tl;drLegal](https://tldrlegal.com/)
- There are so many Applications buit with Lisp, but most of them are more than 20 years old, this [list will be endless](https://www.reddit.com/r/lisp/comments/77tgpl/awesome_common_lisp_application_software/doprwez/) as Rainer Joswig said, so here I wil only include the relevant application.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).


[Expat]: http://directory.fsf.org/wiki/License:Expat
[Artistic License 2.0]:http://directory.fsf.org/wiki/License:ArtisticLicense2.0
[GPL3]:http://www.gnu.org/copyleft/gpl.html
[GPL2]:https://www.gnu.org/licenses/gpl-2.0.html
[LGPL]:http://opensource.franz.com/preamble.html
[AGPL3]:https://www.gnu.org/licenses/agpl.html
[3-clause BSD]:http://directory.fsf.org/wiki/License:BSD_3Clause
[2-clause BSD]:https://opensource.org/licenses/bsd-license.php
[MIT]:https://opensource.org/licenses/MIT
[Proprietary]:https://en.wikipedia.org/wiki/Proprietary_software
[PostgreSQL License]:https://www.postgresql.org/about/licence/
[LLGPL]:https://tldrlegal.com/license/lisp-lesser-general-public-license
[CC0]:https://creativecommons.org/publicdomain/zero/1.0/
