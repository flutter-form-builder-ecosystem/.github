# Maintenance philosophy

Here we try to describe the current philosophy for the maintenance of the different Flutter Form Builder Ecosystem packages.

This package has been created and maintained by volunteers during their free time. It does not have significant sponsorship ([but we are open to have it](https://opencollective.com/flutter-form-builder-ecosystem)) in order to pay people to dedicate exclusive time.
For these reasons, it has been decided to create this document that expresses the philosophy of maintaining the packages so that they can continue to exist and provide value to the community.

## Minimum compatibility with Flutter

For this package to be meaningful, it must always be updated to be compatible with the latest stable version of Flutter and Dart.
This is even more necessary because of the way the components are built, which are based on Flutter widgets. 
Points that will be prioritized to achieve this goal:
- Updated version of Flutter and Dart, with corresponding language changes, component properties and etc. 
- Updated dependencies
- Package structure and example (native setup) updated
- Follow and anticipate changes of future stable versions of Flutter and Dart.

## Prioritize existing and relevant issues

A relevant issue is one that when resolved can offer a minimal benefit to many users or a large benefit to a subset of users.
Anything that is a block to using the package with the latest version of Flutter will be relevant. For example, conflicts with dependency versions, something that should be resolved with the previous point.

### Fix bugs

It is important that the packages are reliable. For this, the correction of bugs that exist in the backlog will be prioritized when deciding which issues to start working on.

### Add features

We will solve functionalities that already exist in the backlog. The choice between the existing ones, will be a decision between the most requested and the fastest/simplest, depending on the availability of the volunteer.

## Avoid breaking changes

Whenever possible and for minimum disruption to the user, breaking changes should be avoided. If they are made, they should be justified and offer value to the user.
You can improve the experience of correcting breaking changes with [`dart fix`](https://github.com/flutter/flutter/blob/master/docs/contributing/Data-driven-Fixes.md).

## Packages priority

As there are several packages, it is necessary to have a priority to initiate the maintenance of each one of them.
For simplicity, the order will be from the most used package to the least used.
You can see the number of downloads of each one [here](https://pub.dev/publishers/flutterformbuilderecosystem.com/packages)
Generally it will be:
1. [flutter_form_builder](https://github.com/flutter-form-builder-ecosystem/flutter_form_builder)
2. [form_builder_validators](https://github.com/flutter-form-builder-ecosystem/form_builder_validators)
3. [form_builder_extra_fields](https://github.com/flutter-form-builder-ecosystem/form_builder_extra_fields)
4. Others

## Contributions

All contributions are welcome. In analyzing each one, we will take into account the above points and the overall vision of each package.
