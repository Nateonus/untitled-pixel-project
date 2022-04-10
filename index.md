# Untitled Pixel Project Docs

## Eh?
This currently-untitled project is a new program designed to help everyone create 2D art assets, in both pixel art or HD vectors.
With a simple set of tools, the program allows users to place down specific pre-made vector shapes, and export them as vector or image files.

## Exporting
Created images can be exported at nearly any resolution. Simply input how many pixels each grid tile is worth, and the program will export an image file at that resolution. Edge smoothing can be enabled or disabled.

![Image](exportshowcase.png) 

_A showcase of 3 types of export on an extremely simple image. Left - Tile size: 32, AA: Enabled. Middle - Tile size: 8, AA: Enabled. Right - Tile size: 8, AA: Disabled. _

## Shapes
The program comes with some useful pre-existing shapes. These are defined in SVG files that are included within the program. 

![Image](shapes.png)

### Creating new shapes
To create a new shape, firstly use one of the existing shape files as a template. These can be found at: (ProjectPath)/Project_Data/StreamingAssets/Vector Shapes. Copy and paste one of the existing files, and give it a unique name.

To edit SVG files, I recommend the use of Inkscape, a free vector editor. 

On loading your new file, you should see the object that you copied, as well as the Inkscape canvas. Select the object and delete it. This leaves you with an empty canvas that is 1 square inch, the required measurement for the program.

Now you can design your own shape. The following rules apply for designing shapes:
- Keep your image inside the canvas.
- Ensure shapes do not have stroke data.
- Any color data will not show in the program.
- Only use one layer.
- Keep it simple - Filters, extensions, and fancy stuff like that may not work as expected.

Save your new shape, and load the program. Your shape should appear in the shape selection panel.

If your shape does not appear, then ensure your layer has an ID of "layer1" (no caps). This can be done by opening the SVG file in a text editor, and checking usually around line 40 if using inkscape. 
