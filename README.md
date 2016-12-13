# RocketBooster

> Drupal 8 Starter Theme for the NASA Goddard Library.

## To Use

- Copy files to new theme folder
	- do not copy the directory so we don't accidentally bring over the git repo
- Rename rocketbooster.info
- Search and replace rocketbooster with your theme name
- Rename the theme folder to your custom theme name
  - theme names should get a year suffix
    - For example: sitename2015

---

-  You will need Node (see installation instructions here: https://nodejs.org) and Gulp (see installation instructions here: http://gulpjs.com/)
-  From the command line, cd into your new theme folder
-  Run "sudo npm install"
-  Run "sudo npm update caniuse-db"
-  Run "gulp"
-  To stop watching, use Ctrl+C

## Notes

### History

RocketBooster was started as a Sass starter theme by Abby Milberg at RepEquity. It was made open source and placed on github under the title of "Boom". It was updated for Drupal 8 and renamed "Chardonnay". It was then expanded by Mitchell Shelton and brought to the NASA Goddard Library.

### To do

- Flexbox (IE11 fixes)
- SVG Icons
- Review/Update Mixins and Extendables
- Review overall structure for Classy integration and Drupal 8 best practices