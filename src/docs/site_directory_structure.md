---
title: Site directory structure
date: 2021.01.13 10:21
section: 01.03
excerpt: <p>The site files organized as follows:</p>
---
The site files organized as follows:
<!--cut-->

    📁 site
        |
        📁 _config
        |     |
        |     setttings.json - main config file
        |     |
        |     📁 templates
        |           |
        |           index.njk - root template
        |           ...
        |           📁 blocks
        |                |
        📁 _system      [custom block templates]
        |    |
        |   [...system stuff...]
        |
        📁 src
        |    |
        |   [site source files]
        |
        📁 static
        |    |
        |   [output]
        |
        index.html
        latidserv.js - local server script
        l4cli.js - command line utility