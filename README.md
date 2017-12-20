# Sass

## Architecture

      scss/
      |
      |- abstracts/ 
      |   |- _functions.scss  # scss function
      |   |- _mixins.scss     # scss mixins
      |   |- _variables.scss  # scss variables
      |   ...                 # etc
      |
      |- base/ 
      |   |- _base.scss       # reset
      |   |- _fonts.scss      # @font-face declarations
      |   |- _helpers.scss    # class & placeholders helpers
      |   |- _typography.scss # basic typography style
      |   ...
      |
      |- components/ 
      |   |- _button.scss     # buttons
      |   |- _carousel.scss   # carousel
      |   |- _cover.scss      # cover
      |   |- _dropdown.scss   # dropdown
      |   |- _navigation.scss # navitation
      |   ...
      |
      |- layout/ 
      |   |- _header.scss     # header
      |   |- _footer.scss     # footer
      |   ...   
      |
      |- pages/ 
      |   |- _home.scss       # home specific styles
      |   |- _contact.scss    # contact specific styles
      |   ...
      |
      |- themes/ 
      |   |- _default.scss    # default theme
      |   |- _admin.scss      # admin theme
      |   ...
      |
      |- vender/ 
      |   |- _normalize.scss  # normalize
      |   |- _jquery-ui.scss  # jQuery ui
      |   ...
      |
      |
      |- main.scss

## [Guidline](https://sass-guidelin.es/)