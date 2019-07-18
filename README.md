[![Code Climate](https://codeclimate.com/github/MITLibraries/dpm_classy/badges/gpa.svg)](https://codeclimate.com/github/MITLibraries/dpm_classy)

DPM_Classy
======

DPM_Classy is a Drupal 8 theme (specifcally a sub-theme of [Classy](https://www.drupal.org/docs/8/core/themes/classy-theme)) that was developed for the [Digital Preservation Management](https://dpworkshop.org/) website.

![Screenshot of DPM Classy in action](https://github.com/MITLibraries/dpm_classy/blob/master/screenshot.png)

Contributing
------------

Please note that this theme uses [SCSS syntax](https://sass-lang.com/documentation/syntax#scss) for its styles - but the compilation must be done by the contributor. Your contributions should include both changes to the source stylesheets (in `/scss`) as well as the compiled stylesheets (in `/css`).

The recommended workflow is to have the following command running in a separate terminal window while you develop:

```
/path/to/repository$ sass --watch scss/:css/
```

This will allow you to commit the same changes to both source and compiles stylesheets in one message.

[For an introduction to this approach to stylesheets, please consult the SASS Basics resource.](https://sass-lang.com/guide)
