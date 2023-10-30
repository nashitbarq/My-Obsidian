
### TEXT

- Type tool
- Type on a path
- Text Wrap
- Clipping Mask on Text
    - Text Layer on Bottom, Image layer on top
    - Go to layer and click “Create Clipping Mask”
        - After clipping:
            - BG Image can be moved to adjust background
            - Text can be moved
            - Both image and text can be moved together (select both layers)
            - Click on text and hold Ctrl to move text (select text layer first)

### Cropping

- Use, Presets, Ratio, W x H x Resolution, top-bar: Straighten, Grids, Content-Aware

### Resolution

- DPI, Resizing Images

### FX

- FX: Drop Shadow (Using Global shadow affects all text-layers [that’s what instructor said])
- Bevel and Emboss
- Color Overlay
- Stroke
- Gradient Overlay

### Color Grading

- Auto: Tone / Color Contrast
- Vibrance / Sat
- Hue / Sat
- Levels

### Selection tools

- Quick: Subtract, Add options, Enhanced edge to automatically smoothen the selection
    - Contract selection (shrink): Select → Modify → Contract
- Magic
- Object

### Layers

- Moving an image between canvases
- Merge layers

### Pen Tool

- Shape and Layer options

### Marquee Tools

- Rectangle, Ellipse, Single row, Single column

### Masking

:: This procedure follows non-destructive workflow. ::

### Layer Masks

- How to: Make a selection → Go to layers panel → Bottom panel → Click on create a Mask
- Image can be moved, Mask can be moved, Both can be moved.
- Density and Feather can be adjusted.

### Select and Mask

:: Includes advanced options for masking. ::

- View Mode (Preview your masked object in different view modes)
- High Quality Previews
- Edge Detection → Radius, Smart Radius
- Output: Decontaminate Colors: Before you output, you can check the “decontaminate colors” box to **remove color fringe**. This step is necessary when your subject is against a contrasting color background.
- Shift Edge: + or - edges
- Output to
    - New Layer
    - New Layer with Layer Mask
    - New Doc
    - New Doc with Layer Mask
- Refine Edge Brush Tool: Refine further - Very useful to further refine subject’s hair
- Subject Selection Tool

### Smart Objects

“If you make an image really small, photoshop goes like ‘okay I am gonna get rid of all the pixels I do not need’ and when you make it bigger they’re just not there anymore and that results in low photo quality۔”

**Making smart object:** Right Click on layer and select CONVERT TO SMART OBJECT

**Vector Graphics:** We can directly copy a vector object from Illustrator and paste it in PS, we are presented with 4 choices. Paste as:

- Smart Object [Best choice]
- Pixels
- Path
- Shape Layer

**Rasterize Layer**: Right click and choose rasterize

**Back to Illustrator:** You can double-click on thumbnail icon in layers panel, and the smart object will open back in Illustrator as it can be modified. But the opened one will be the “copy” that we made to PS from AI, not the original logo that we pasted from. In short, we are editing a copied vector smart object that has been imported by Illustrator.

- Modify in AI and click save. Changes will reflect in PS
- Works the same for inDesign and Illustrator
- We can also use File → Place Embedded → Select AI file → Place Vector → Ok

**Drawbacks:**

- File size will be bigger because no pixels are destroyed because of smart object feature.
- Some of the effects like “Lens Blur” will not work with Smart Objects.

### Transform and Warp Tools

Edit → Transform:

- Scale
- Rotate
- Skew
- Distort
- Perspective
- Warp

### Spot Healing Brush

- Brush size will depend on image
- Crank your hardness down to zero (this gives a nice, even edge)

**Bad way**

- Using straight on an image
- Also known as destructive editing, cause we can not go back
- If we want to go BACK, go to File → Revert: This gets it back to when we first opened the document

**Good / Pro way**

- With brush tool selected, make an empty layer on top of image
- In the top-toolbar, `Sample All Layers`, Type: `Content-aware`, Mode: `Normal`
- Start healing on the empty layer and changes will reflect on the image

**Dealing with artificial / plastic look**

- In case the image looks artificial / plastic, adjust / reduce the top-layer (empty layer) `opacity` until it starts lokking natural (until you find the balance of real life, like muting the marks and blemishes, rather than turning them off)

### Content-Aware Scale

- Just like we can crop-in the images, we can also crop them out. It gives is more canvas to work with.

Protecting Areas:

- If you scale an image, but object, say paper, is also being scaled. We can omit this behavior by protecting this area, paper in this case,
    - Take any selection tool
    - Select the object edges
    - Go to Select → Save Selection
        - Give this selection a name
        - Now, go to Select → Deselect
    - Now go to Edit → Content-Aware Scale
        - Now there is an option in top-bar that says protect, choose the previously saved selection
        - Use Content-Aware Fill now and it will protect the paper/

### Save as Adobe PDF

- Options:
    - `uncheck` Preserve Photoshop Editing Capabilities (Large Size)
    - `uncheck` Embed Page Thumbnails
    - `check` Optimize for Fast Web Previews
    - Adobe PDF Preset: `High Quality Print`