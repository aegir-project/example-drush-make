# Aegir Example Repository
## Makefiles in Git

Use this repository as an example for your project.

When creating your platform, use "docroot" as your "Repository docroot" (or choose your own. When using makefiles, this folder is where drush make builds the drupal code.)

Use "PUBLISH_PATH/drupal.make" for "Makefile". Make sure PUBLISH_PATH is what you entered under the **Title** of the platform node.

## Editing your makefile

You can put anything in your makefile as long as it processes successfully.

Adding a "profile" will include that install profile and all dependencies.

You can include custom repositories now, and soon you will be able to include "local" code right in the same git repo.  (coming soon, pending a patch to Aegir & Drush).



