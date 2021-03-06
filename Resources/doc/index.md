scheb/two-factor-bundle
=======================

This Symfony2 bundle provides two-factor authentication for your website.

By enabling the bundle it will hook into the authentication process and listen for authentication events. If the user entity supports two-factor authentication, it will not grant access until the user enters a valid authentication code.

The bundle supports multiple authentication methods.

## Index ##

  - [Installation](installation.md)
  - [Configuration](configuration.md)

## Authentication Methods ##

The bundle supports the following authentication methods:

  - [Google Authenticator](google.md)
  - [Authentication code sent via email](email.md)

You can also enable multiple authentication methods at the same time. This allows you to create a multi-level authentication process (three-factor and even more).
