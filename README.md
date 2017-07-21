# Twitter Bootstrap Theme with Overview

A theme for [ApiGen](http://www.apigen.org/) that matches [Twitter Bootstrap v4.0.0-alpha.6](https://github.com/twbs/bootstrap/releases/tag/v4.0.0-alpha.6).

**This fork supports showing an overview page.**

![Twitter Bootstrap Theme](screenshot.png)

## Installation

    composer require wonderpush/apigen-theme-bootstrap --dev

## Usage

Add `--template-config vendor/wonderpush/apigen-theme-bootstrap/src/config.neon` to ApiGen command like :

    apigen generate --source overview.md --source app --destination docs/api/v1 --template-config vendor/wonderpush/apigen-theme-bootstrap/src/config.neon

Make sure to list one overview.md file in the source.
