# Organic Groups Subgroups

## Description

The Organic Groups Subgroups module (also referred to as the 'og-subgroups'
module) enables a user with the proper permissions to build group hierarchies
(or tree) by nesting groups under other groups. Simple or complex group
hierarchies can be easily created using subgroups.

Subgroups can automatically inherit the users and/or permissions of the parent
group, but can also have additional specific users and permissions. Members can
collaborate effectively within their respective groups and subgroups, sharing
relevant content and resources.

When a hierarchy has been established, user memberships and/or content posted to
a group can be propagated up, down or sideways along the tree. So when a user
joins a group, their membership can also get created in other parent, child or
sibling groups. Separate propagation settings can be applied for content and
membership propagation.

There are two types of propagation:

1. The first type is **Group user inheritance** that allows users of a group to
propagate to subgroups.

2. The second type is **Group user permission inheritance** that determines how
permissions are applied to inherited users including group administration and
access to group content.

This allows an entity's membership to be propagated up or down the group
hierarchy when adding a new group or group content to an existing group.

## Installation & Configuration

Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules)

For basic user membership inheritance:
1. Go to the OG field settings page (admin/config/group/fields).
2. Select a bundle to attach the inheritance field to using the Entities dropdown.
3. Select the Group user inheritance field in the Fields dropdown.
4. Click 'Add field'.
5. Navigate to the content type to configure field defaults if desired.

This module provides two fields under /admin/config/group/fields:
- Group user inheritance: Determines if the subgroups of a group will inherit its users
- Group user permission inheritance: Determines how permissions are given for inherited users

For more information, search the Drupal 7 version issue queue, and this module's
issue queue. Some helpful posts:
- https://www.drupal.org/project/og_subgroups/issues/1969242
- https://www.drupal.org/project/og_subgroups/issues/2572931
- https://www.drupal.org/node/1345212

## Dependencies

- [Organic Groups](https://backdropcms.org/project/og)

## Current Maintainers

- Ported to Backdrop CMS and maintained by [argiepiano](https://github.com/argiepiano)
- Seeking co-maintainers

#### Drupal 7 version maintainers:

- [bshilt](https://www.drupal.org/u/bschilt)
- [amitaibu](https://www.drupal.org/u/amitaibu)
- [ezra-g](https://www.drupal.org/u/ezra-g)
- [mpotter](https://www.drupal.org/u/mpotter)
- [kenianbei](https://www.drupal.org/u/kenianbei)
- [mstef](https://www.drupal.org/u/mstef)
- [hefox](https://www.drupal.org/u/hefox)

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
