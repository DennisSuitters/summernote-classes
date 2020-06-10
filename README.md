# summernote-classes v0.2
A plugin for the [Summernote](https://github.com/summernote/summernote/) WYSIWYG editor.

summernote-classes adds functionality that indicates the current clicked on element inside the editing area, if classes for language and options are set, the classes will displayed next to the selected element which are clickable to toggle that class for the selected element with indication if the element contains the class or not. Classes not outlined in the plugin lang, or options will simply be displayed as the Element Node Type without the class options.

Included are some sample classes from Bootstrap 4, feel free to add, edit or remove.

![summernote-classes](summernote-classes.gif)


### Installation

#### 1. Include JS

Include the following code after Summernote:

```html
<script src="summernote-classes.js"></script>
```

#### 2. Supported languages

Currently available in English!

#### 3. Options
The classes should be added in the plugin directly, the array in the language part must match up with the array in the options section.
There is now an option `disableTableNesting: false|true` within the plugin that if set to true will disable the Table Button in the Toolbar to stop inserting a Table inside a Table.

#### 4. Check out our other Summernote Plugins via our main Github page.
- [Diemen Design](https://github.com/DiemenDesign/)
