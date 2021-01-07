
Comment Permissions module
======================

The Comment Permissions module enables control of commenting by user role and
by node type.  Additional user permissions for selected node types are added
to the user access system so you can configure commenting with more control
than Drupal core provides.

> Note that "reply" links below comments may still appear for users without the
  permission to add comments.  This is unfortunate, but I haven't found a
  workaround.  See http://drupal.org/node/185855 for more information.
  Of course, the links can easily be removed in the theme layer.


Requirements
------------

This module requires that the following modules are also enabled:

 * Comment module

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Visit the configuration page under Administration > Configuration > Comment
  (admin/config/comment) and enable the extended comment permissions for
  certain content types here.

- Go to Administration > Configuration > User accounts > Permissions
  (admin/config/people/permissions) and configure which roles can post comments
  for the these content types.

> NOTE: Comments must already be enabled for this module to do anything.
      This module simply removes the ability for a user to post comments if
      they don't have the right permissions.
      It does not add the ability to comment on node types that don't have
      commenting enabled!

Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/comment_perm/wiki/Documentation.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/comment_perm/issues.

Current Maintainers
-------------------

- [Jen Lampton](https://github.com/jenlampton).
- Seeking additional maintainers.

Credits
-------

- Ported to Backdrop CMS by [Jen Lampton](https://github.com/jenlampton).
- Maintained for Drupal by [Sorin Dediu](http://drupal.org/user/1420228)

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
