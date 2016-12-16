# Sketch to Click-through HTML

Convert your artboards into HTML pages.

##### Installation

1. Download the plugin.
2. Double click "Sketch to HTML.sketchplugin" to install it.


## How it works ##

First, specify how your artboards should link to one another. E.g. If clicking a button on artboard 1 should take user to artboard 2, select the button layer and run the `Link selected layer to...` command. Then select artboard 2 in the pop up that apprers. You can also fix layers to one of the four positions. If you got a fixed nav, this can be handy. 

Once done with the set up, run the `Export to HTML`.


| Command                     | Description |
|:----------------------------|:----------------------------------------------------|
| Link selected layer to...   | Link a layer to an artboard in the current page |
| Fix selected layer to...    | Fix a layer to one of the four positions: top, right, bottom, left  |
| Export to HTML              | Export current page artboards into html files, in a folder named after the Sketch file |
| Clear selected layer's HTML | Clear the HTML options set for the selected layer  |
| Clear current page          | Clear all the HTML options set in the current page |
| Show HTML config for selected artboard | Get an alert message listing HTML options set for current artboard |

## Limitations ##

1. Only the artboards of the current page will be exported.
~~2. A layer you wish to link or fix has to be a top-level layer, meaning it cannot be nested inside another layer.~~
3. Make sure each artboard in the page has a unique name.

## What's next? ##
- [ ] Remove limitation #1 - perhaps user selects which pages
- [x] ~~Remove limitation #2 - Link or fix nested layers~~
- [x] ~~Open folder after export~~
- [ ] Export for mobile apps - artboards embedded in a mobile frame, similar to Invision
 

## Feedback & pull requests ##

All are welcome  :)


## License ##

What's that?!
Do as you wish and share the good stuff.
