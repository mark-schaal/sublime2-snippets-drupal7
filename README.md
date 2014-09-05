sublime2-snippets-drupal7
=========================

Reusable Sublime Text 2 snippets for Drupal 7.x API

## Installation
Place any of the .sublime-snippet files into your local ../Sublime Text 2/Packages/User directory and restart Sublime Text

## Current Snippet Tab Triggers
* **module_info** -- Triggers template for populating a module.info file
* **module_install** -- Triggers template for populating a full module.install file
* **hook_menu** -- Triggers template hook_menu()

## Development Notes
It appears that Sublime Snippets are not intended to house multiple <code><snippet></code> declarations; therefore, we should focus on converting this into a .sublime-completions file as documented here(http://docs.sublimetext.info/en/latest/reference/completions.html)
