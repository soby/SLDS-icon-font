# SLDS-icon-fonts

[The Salesforce Lightning Design System (SLDS)](https://www.lightningdesignsystem.com/resources/icons "SLDS") currently offers a robust, abstract SVG icon system. However, there may be situations where an additional icon-font set would be helpful.

Well, here it is.

This icon-font set is based on the SLDS SVG set (version 0.10.1) and generated by created with [Icomoon](https://icomoon.io/ "Icomoon").

## Basic Usage
add prefix `.sldsicon-` then follow this naming scheme: `[categoryName]-[fontName]`.

Example: `<i class="sldsicon-utility-add"></i>`.

## Caveats
The only caveat is with the SLDS `doctype` icons which use two layers. The markup to render those looks like this:

```
<span class="sldsicon-doctype-audio">
    <span class="path1"></span><span class="path2"></span><span class="path3"></span><span class="path4"></span>
</span>
```

Check out [a demo](http://codescience.github.io/SLDS-icon-fonts/).

## Getting Started
There are a couple of options here:
* Clone the repo: `git clone https://github.com/CodeScience/SLDS-icon-fonts.git`
* Install with npm: `npm install`

### Contributing
1. `npm install`
2. `gulp`
3. `gulp serve`
4. Make your local edits and submit a pull request.