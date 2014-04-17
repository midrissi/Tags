## Custom Widget for [Wakanda](http://wakanda.org/): jQuery Tags Input

Do you use tags to organize content on your site? This widget will turn your boring tag list into a magical input that turns each tag into a style-able object with its own delete link. The widget handles all the data - your form just sees a comma-delimited list of tags!

The widget is an implementation of the [Tags](http://xoxco.com/projects/code/tagsinput/) jQuery plugin

### Properties
This widget __Tags__ has the following properties: 

* __interactive__: If you do not want to provide a way to add tags, or you would prefer to provide an alternate interface for adding tags to the box, you may pass an false into this optional parameter.
* __defaultText__: Default text to be displayed informing the user to add a new tag.
* __removeWithBackspace__: By default, if the cursor is immediately after a tag, hitting backspace will delete that tag. If you want to override this, set this option to false
* __minChars__: Minumum chars to be accepted if a new tag was created.
* __maxChars__: Maximum chars to be displayed.
* __placeholderColor__: The RGB color of the placeholder

And has the following methods:
* __add__: Add a new tag
* __remove__: Remove the specified

And has the following events:
* __onAddTag__: This event will be triggred when a new tag has been added.
* __onRemoveTag__: This event will be triggred when a new tag has been deleted.
* __onChange__: This event will be triggred when a new tag has been added or removed.

### Install
For more information on how to install a custom widget, refer to [Installing a Custom Widget](http://doc.wakanda.org/WakandaStudio0/help/Title/en/page3869.html#1027761).

For more information about Custom Widgets, refer to [Custom Widgets](http://doc.wakanda.org/Wakanda0.v5/help/Title/en/page3863.html "Custom Widgets") in the [Architecture of Wakanda Applications](http://doc.wakanda.org/Wakanda0.v5/help/Title/en/page3844.html "Architecture of Wakanda Applications") manual.
