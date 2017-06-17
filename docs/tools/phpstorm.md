# Using PhpStorm for CiviCRM Development

[PhpStorm](https://www.jetbrains.com/phpstorm) is a commercial IDE which is popular among CiviCRM developers.


## General project setup

* Use the root directory of your CMS as your project root (otherwise in-app debugging won't work)
* You can speed up PhpStorm's indexing process by taking the following steps to ignore most files:
    1. Settings > Directories
    1. Mark all directories as "Excluded"
    1. Drill down to find the "civicrm" folder and mark it as "Sources"

## Code style setup

Create the 'CiviCRM' code styling preference:

1. Open you current project's properties: File > Settings
1. Create the CiviCRM code styling preference: Code Style > Manage > Save as, then indicate 'CiviCRM'
1. In the 'Code style' sub-menu, select 'PHP', then 'Set from ...' at the far right, Predefined Style > Drupal (this sets options across all tabs of the dialog)
1. In the 'Code style' sub-menu, select 'Javascript', then 'Set from ...' at the far right, PHP (this replicates all PHP settings to the Javascript section)
1. Click 'Apply' at the bottom of the screen

That's it. You can now use this code style on all future CiviCRM-related projects. If you are only developing for CiviCRM, you can also copy this style to the 'Default' style.


## Running CiviCRM's automated tests from within PhpStorm

TODO: write this section, drawing on some content here:

https://wiki.civicrm.org/confluence/display/CRMDOC/Tests+in+phpstorm


## XDebug integration

TODO

