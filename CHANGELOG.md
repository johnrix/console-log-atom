## 0.1.0 - First Release
* can generate an empty console.log function
* if a value is selected, generates a console log of that value, with a string identifier on next line.

## 0.2.0 - Fixed documentation
* More thorough documentation to make app easier to use

## 0.3.1 - Fixed Cursor Positioning
* he cursor is placed between log and the first bracket, now the cursor was placed within the brackets.

## 0.6.2 - Added include semi-colons configuration Option
* Choose whether you want to include semi-colons at end of console.log function. Depending on the linting standard you use, you can choose to include semicolons. **Defaults to no semi-colons**

## 0.7.0 - Added identifier Case configuration Option.
* Choose whether to retain case of selected text when creating identifier. **Defaults to creating an identifier in capital case of selected text**

## 0.8.0 - Added console.log option with JSON.stringify
* Can generate a console.log function with a JSON.stringify method using ```ctrl-o``` or ```ctrl-alt-o```

## 0.9.1 - Smart detection of objects
* If selected text is the variable being defined to create an object, places console.log after object has been created to prevent any code breaks.

## 0.10.0 - Added Deconsoler
* ```ctrl-shift-D``` will clean out all the lines that contain console.log statements in the file.

## 0.11.0 - Added background and text styling
* Background and text styling of console.log identifier now available. will only work for logging in chrome dev tools console.

## 0.12.0 - Moved console.log with background and text styling to separate keymaps
* ```ctrl-alt-c``` - Will mimic the functionality of ```ctrl-alt-l``` but will include background and text styling if applicable.
* ```ctrl-alt-s``` - Will mimic the functionality of ```ctrl-alt-o``` but will include background and text styling if applicable.

## 1.0.0 - First Stable Version !

## 1.1.0 - First incomplete build of smart function console.logging
* Console log statement is placed inside the function if param is chosen
* console log statement is placed outside the function if function name is chosen

## 1.2.0 - Smart Conditionals Logging (early release)
* if a variable used in a definition of an if statement is used, so that the logging is not lost if the condition doesn't pass, the insert is placed on the line above the if statement.

## 1.3.0 - Smart conditional logging, with improved behaviour for chained Conditionals
* if a variable used in a definition of an if statement is used, so that the logging is not lost if the condition doesn't pass, the insert is placed on the line above the if statement. For subsequent conditionals, the insert is placed within the conditional

## 1.4.0 - Config Option added to include String TEST for identification if no text selected
* Rather than include a dumb ```console.log()``` insert, if you can select to have ```console.log('TEST')``` inserted, which will show up as the code run past it.

## 1.5.0 - First conditional inserts now includes a 'CONDITION passed' insert within conditional
