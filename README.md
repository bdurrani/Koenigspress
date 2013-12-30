#Königspress

Octopress theme with emphasis on typography.
The main goal of this theme is providing a similar reading experience to a a high-quality typeset book or .pdf file.
We would recommend this theme for site content requiring lengthy lecture and high immersion (e.g. memoir-like blogs, diaries, short stories, novellas).

##Demo

[Märzwasser](http://mw.chymera.eu)

## Install

From your octopress blog root directory:

    $ git clone https://github.com/TheChymera/Koenigspress.git .themes/Koenigspress
    $ bundle exec rake install[Koenigspress]
    $ bundle exec generate

## Customize

The theme can be customized just as the default octopress theme - by edditing the files under `/sass/custom` and under `/source/_includes/custom`.
Additionally, Königspress also allows font and logo customization.

### Logos

The logo displayed in the upper right corner of the screen can be changed by changing the `/source/logo.png` file.
The "favourite icon" (displayed by many browsers in the tabs or bookmarks list) can be changed by changing the `/source/favicon.png`.
Both these changes will only take effect after you run the next 

    $ bundle exec generate
    
Additionally, favicon changes may take a while to become visible due to browser caching.

You can customize the way in which the logo is displayed by editing its HTML under `/source/_includes/logo.html` and its CSS at the end of the `/sass/partials/_blog.scss` file.

### Fonts

Our emphasis on typography goes hand in hand with permitting the user to choose a typographical style to best complement his content.
We use the convenient [Google Fonts](http://www.google.com/fonts#AboutPlace:about) framework for importing free, open, and high-quality webfonts.

A number of these (which we believe are in tune with our design paradigm) are already loaded under `/source/_includes/custom/head.html`.
You can add any other font from Google Fonts via that file.
Of these fonts the ones to be used are specified `/sass/base/_typograpphy.scss` file.

## Contribute

Please report any glitches or them inconsistencies that may bother you (preferably alongside a link to your website).
We highly appreciate any forks, pull request, or any other kinds of contributions.


##Meta

Released under the GPLv3 license.
Project led by Horea Christian (address all correspondence to: h.chr@mail.ru, or contact via [chymera.eu](http://chymra.eu)).
