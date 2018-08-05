# How to Deploy this Site

These are the settings that need to be updated in order to deploy this development site over the live site. 

1. Go to the Remote CSS plugin page and insert this link: https://api.github.com/repos/XAce90/nyc-wordcamp/contents/2018/main.css. Output mode should be set to Add-on.
2. You'll get a notice saying @imports were stripped from the CSS, and you should use the Fonts tool to add webfonts. Follow that link, and add this code under the Google WebFonts field: @import url('https://fonts.googleapis.com/css?family=Sansita|Source+Sans+Pro');
3. Remove custom CSS from the Theme Customizor.
4. Copy Pages and Page Content from dev to the live site.
5. Update menus
6. Test! Look around the site. Anything break?