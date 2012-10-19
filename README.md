GridRuler
=========

"There is no such thing as pixel-perfect web design". But we can check if the ratios are ok.

This is a ruler for the web, based on PPK's drag and drop JavaScript.

## A simple why
At Mirabeau we design with ratios. Usually they're made up from the client's logo and grid. To check if the design has the right proportions, some designers use layers in Photoshop. We call this 'the Ruler'. I worked out a simple version of it, with three blocks.

## Features
- Switch color, by clicking the first icon;
- Change the block sizes by clicking the second icon. You get three prompts where you can add a number, without a unit. The script sorts the numbers;
- Move ruler with dragging and dropping;
- Move ruler with keyboard, by clicking the third icon. Hold shift to move it 10px at a time instead of 1px. Just like in Photoshop.

## Known issue
- Doesn't work nicely in IE and touch devices;
- Some browsers can't show the icons correctly;
- It needs better text/usability for the prompt;
- You need to fill in some numbers in the prompt in order to make it disappear. I think it needs to go away if you click cancel three times.