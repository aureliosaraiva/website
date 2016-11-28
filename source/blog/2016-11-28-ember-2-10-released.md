---
title: 
author: 
tags: Releases
---

## Ember.js




## Ember Data




## Ember CLI

Generic upgrade instructions.

- https://github.com/ember-cli/ember-new-output/compare/v2.9.1...v2.10.0
- https://github.com/ember-cli/ember-addon-output/compare/v2.9.1...v2.10.0

### Ember CLI 2.10

Last version which will support Node.js v0.12.

- `package.json` sorting.
- Concatenation ordering forced to be consistent. https://github.com/ember-cli/ember-cli/pull/6081
- Concatenation uses system-independent line separator. https://github.com/ember-cli/ember-cli/issues/6300
- Updated bundled `npm` to `npm@3`. https://github.com/ember-cli/ember-cli/pull/6306
- Removed `ember.js@1.13` from the default testing matrix.  

### Ember CLI 2.11-beta

Highlight feature: Ember.js provided as `npm` module: `ember-source`.

- Bundles new version of `ember-welcome-page`.
- Ensures that we successfully save addons during installation. https://github.com/ember-cli/ember-cli/pull/6319
- Update `leek` to prevent warning on outbound analytics message failure.
- Watch vendor by default. https://github.com/ember-cli/ember-cli/pull/6436
- Better cleanup on exit. https://github.com/ember-cli/ember-cli/pull/6423
- Performance improvement by reducing merge-trees. https://github.com/ember-cli/ember-cli/pull/6453
- Allow a custom resolver to be passed in. https://github.com/ember-cli/ember-cli/pull/6254

Feedback requested:

- People with _large_ `vendor` folders.
- Testing with `ember-source`.