Phing Drupal Distributions
==========================

Phing build scripts for working with Drupal distributions.

To use with your distribution:

1. Copy this directory into a sub-directory called 'build' in your profile

2. Copy the 'examples/build.xml' and 'examples/build.properties' to the
   top-level directory of your profile.

3. Modify 'build.properties' to suit your needs.

4. Run 'phing -l' to see what targets you can build!

Installing dependencies
-----------------------

First, you need to install Phing:

  pear channel-discover pear.phing.info
  pear install phing/phing

Then you need to install VersionControl_Git:

  pear install VersionControl_Git-0.4.4

