# Theme
Name: Siggen
Author: Gratis Themes (https://github.com/GratisThemes)
License: GNU General Public License v3

# Copyright
Siggen WordPress Theme, Copyright (C) 2016-2019, Gratis Themes
Siggen is distributed under the terms of the GNU GPL v3

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

-----------------------------------------------------------------------------

# Libraries
# The theme bundles the following third-party resources:

normalize.css v8.0.0
License: MIT
Source: github.com/necolas/normalize.css

Font Awesome 4.6.3 by @davegandy
  Font License
    Applies to all desktop and webfont files in the following directory: font-awesome/fonts/.
    License: SIL OFL 1.1
    URL: http://scripts.sil.org/OFL

  Code License
    Applies to all CSS and LESS files in the following directories: font-awesome/css/, font-awesome/less/, and font-awesome/scss/.
    License: MIT License
    URL: http://opensource.org/licenses/mit-license.html

-----------------------------------------------------------------------------

# Images

Default header image
by Vaping360
Link: https://www.flickr.com/photos/vaping360/16161316908/
License: https://creativecommons.org/licenses/by/2.0/

-----------------------------------------------------------------------------

# Changelog

1.0.0 - 2016.04.09
- Initial release

1.1.0 - 2016.05.27
- Reworked archive title icons
- Added breadcrumbs

1.1.1 - 2016.06.11
- Fixed naming of global variables

1.1.2 - 2016.06.11
- Fixed naming of global variables

1.2.0 - 2016.06.17
- Removed HTML5 Shiv
- Updated and moved Font Awesome
- Fixed various style bugs and issues
- Fixed various RTL style bugs and issues
- Fixed naming of global social media variable
- Simplified menu logic and cleaned up JS file

1.2.1 - 2016.09.06
- Removed Google and WhatsApp social icons
- Fixed showing of social media wrapper when no social icons are set
- Replaced JS detection in functions.php with one in js/functions.js
- Cleaned up template parts, post formats and image.php
- Various code and style fixes
- Fixed header
- Fixed default header image not working
- Removed default background image due to WordPress not fully supporting it yet
- Removed customize logo setting in favor of native WordPress custom logo support
- Fixed only logo or site-title showing
- Included copyright information in style.css and readme.txt
- Escaped various user inputs
- Included complete Font Awesome package and license decleration
- Replaced custom get_the_archive_title filter with JS solution
- Removed closing ?> tag in required files (customize.php and theme_functions.php) to prevent possible "Header already sent" errors
- Added prefix to enqueued styles and scripts in funtions.php

1.2.2 - 2016.09.19
- Changed screenshot
- Removed theme author URL from footer credit

1.2.3 - 2016.11.06
- Enqueued comment-reply script
- Replaced customized css styles being added to the header with wp_add_inline_style option
- Added editor stylesheet

1.2.4 - 2017.05.18
- Updated theme information for author rebranding
- Fixed usage of get_the_permalink instead of the_permalink on .post-thumbnail and .read-more in template-parts/loop.php
- Simplified js/functions.js
- Added table of contents to style.css

1.3.0 - 2018.12.20
- Fixed and improved multiple layout and styling issues
- Improved post formats support
- Updated theme information for author rebranding
- Removed breadcrumbs
- Updated language file
- Added support for the_privacy_policy_link
- Improved editor styles
- Removed jQuery from functions.js
- Added filter for archive titles
- Removed "center widgets" setting