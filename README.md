# Drupal -> Jekyll Export

A simple module for exporting content from Drupal 7, into a format (Markdown only) suitable for Jekyll.

It should work out-of-the-box (provided you also install my [Markdownify module](https://github.com/lukaswhite/Drupal-Markdownify), though the code's quite simple & reasonably well documented, should you need to alter it for your needs.

Once you've installed the module, browse to:

_admin/config/system/jekyll-export_

..select the content types to export, enter the name of the layout you want the YAML to specify, and hit "Run Export".

The result: a zip file, containing all the specified nodes in Markdown format.  You should then be able to copy the contents into the _posts folder of your Jekyll site.



Lukas White
hello@lukaswhite.com