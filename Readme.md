<h1 align="center">InGrafiti</h1>

<p align="center">
  <strong>A photo editor for Windows in the Photoshop mould - layers, masks, selections, filters and on-device AI - with nothing ever uploaded.</strong>
</p>

<p align="center">
  <img alt="platform" src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078d4">
  <img alt="dependencies" src="https://img.shields.io/badge/dependencies-none-brightgreen">
  <img alt="telemetry" src="https://img.shields.io/badge/telemetry-none-555">
  <img alt="offline" src="https://img.shields.io/badge/works-offline-7c5cff">
</p>

---

## What it is

A full layer-based photo editor: pixel, text, shape, adjustment and fill layers,
all 27 blend modes, masks, clipping masks, layer styles, 47 tools, 16 editable
adjustment layers, 50 filters, Free Transform, paths, Liquify, and layered PSD
files that open and save with their layers intact.

The part that matters most is where the work happens. **Everything runs on your
machine, including the AI.** Removing a background, taking an object out of a
photograph, enlarging a picture 4x, restoring a face: the models are installed
with the application and run on your processor. No account, no subscription, no
upload, and they all work with the network switched off.

That is the whole point of it. The features that every online editor charges a
subscription for are the ones that most obviously should not involve sending
somebody your photographs.

---

## Download

Grab the latest **`InGrafitiInstaller.exe`** from the
[Releases page](https://github.com/FadyAzzi/InGrafiti/releases) or
[Direct Link](https://github.com/FadyAzzi/InGrafiti/releases/latest/download/InGrafitiInstaller.exe).

Run it and follow the wizard.

**Requirements:** Windows 10 or 11, 64-bit. Nothing else.

Nothing else to install. The installer carries everything InGrafiti needs,
including the machine-learning models. There is no Python to set up, no
runtime to add and no model download on first use.

---

## Features

### Layers

Pixel, text, shape, adjustment, fill (solid, gradient, pattern) and group
layers. All 27 blend modes plus Pass Through for groups, opacity and fill
opacity, layer masks with density and feather, clipping masks, locks, and layer
styles: drop shadow, inner shadow, outer and inner glow, bevel and emboss,
satin, colour, gradient and pattern overlays, and stroke. Layers keep the pixels
you move off the canvas.

### Tools

47 of them, on Photoshop's keys, each one explaining what it is for at the top
of its own settings panel.

- **Select** - rectangular and elliptical marquees, Lasso, Polygonal Lasso,
  **Magnetic Lasso** (the line snaps onto the edge that is really there),
  Magic Wand, **Quick Selection** and **Object Selection**
- **Retouch** - Spot Healing with three fill methods, Healing Brush, Patch
  (including content-aware), Red Eye, Clone Stamp, History Brush
- **Paint** - Brush, Pencil, Colour Replacement, three Erasers, Gradient,
  Paint Bucket, Blur, Sharpen, Smudge, Dodge, Burn, Sponge
- **Draw and type** - Pen, Path Selection, Type, and seven shape tools
- **Everything else** - Move, Crop with straighten, Slice, Eyedropper, Ruler,
  Artboard, Puppet Warp, Hand and Zoom

Free Transform scales, rotates, skews, distorts and applies perspective. Brush
tips, roundness and angle are shown on the cursor as the shape they actually
are, not as a circle standing in for one.

### Adjustments

16 adjustments, each usable as a layer that stays editable: Brightness/Contrast,
Levels, Curves, Exposure, Vibrance, Hue/Saturation, Colour Balance, Black and
White, Photo Filter, Channel Mixer, Invert, Posterize, Threshold, Gradient Map,
Selective Colour and Desaturate. Plus Auto Tone, Auto Contrast, Auto Colour,
Equalize, Shadows/Highlights and Replace Colour.

### Filters

50 filters in the usual categories - Blur, Distort, Noise, Pixelate, Render,
Sharpen, Stylize and Other - with a live preview on the canvas, plus Liquify.

### Selections

Add, subtract and intersect, feather, expand, contract, border, smooth, grow,
similar, Colour Range, Quick Mask, and saved selections as channels.

### Files

Opens PNG, JPEG, WebP, TIFF (all pages), GIF (all frames), BMP, ICO, TGA, PSD
and PSB with layers, groups and masks, and its own `.ingx` layered format.

Opens **camera RAW** as well - Canon, Nikon, Sony, Fujifilm, Olympus, Panasonic,
Pentax, Adobe DNG and around forty more - asking about white balance, exposure
and highlight recovery rather than guessing.

Saves `.ingx` and layered PSD. Exports to PNG, JPEG, WebP, TIFF, BMP, GIF, ICO
and TGA with a live size estimate, or to an animated GIF, WebP or APNG from the
Timeline. Prints with a page preview. Copy and paste with other applications
keeps transparency. A batch processor resizes, corrects, sharpens, watermarks
and converts whole folders, and can run an action you recorded yourself.

### The workspace

Panels dock down the right in groups you can fold away: Layers, Channels, Paths,
History, Properties, Adjustments, Presets, Colour, Swatches, Navigator,
Histogram, Info, Timeline, Actions and Artboards.

A panel opens against the tool strip with whatever the tool in your hand needs -
its settings as labelled sliders with numbers rather than a cramped strip, plus
canvas sizes under Crop, elements under the shape tools and text styles under
the Type tool. It floats over the picture rather than pushing it aside.

A search bar in the menu bar finds any of the 343 tools and commands by name.

### Bring your own

Fonts and brush tips go in a folder of their own and are picked up on the next
start. **Nothing is installed into Windows**: a font added this way works in
InGrafiti and changes nothing outside it, which needs no administrator. Colour
look-up tables (`.cube`) and your own adjustment presets import from the Presets
panel.

### Safety

Undo with a History panel, snapshots you can name and paint back to with the
History Brush, and crash recovery that brings back unsaved work after a power
cut.

---

## The AI, on your own machine

Sixteen features, grouped by what you are trying to do rather than by which
model happens to run. All of them work offline.

### The background
- **Remove background** - cut the subject out and leave it transparent
- **Change background** - put the subject on a colour or another picture
- **Blur background** - a portrait look, with a live preview
- **Replace the sky** - a new sky, matched to the light in the picture

### Take something out
- **Remove an object** - click the thing you do not want and the hole is filled
- **Remove text** - take writing out of a photograph
- **Repair damage** - scratches and creases on an old photo

### People
- **Retouch a portrait** - smooth skin and keep the texture
- **Restore a face** - sharpen a small or blurred face

### Make it better
- **Reduce noise** - clean up a grainy phone picture
- **Enlarge** - 2x or 4x with real detail rather than a smooth stretch

### Light and depth
- **Lens blur** - depth-aware, near and far
- **Relight** - move the light around the subject

### Choose part of the picture
- **Select subject** - select whatever the photo is of
- **Select an object** - click a thing and select just that
- **Smart reframe** - crop to a new shape, keeping the subject

**Honest about the slow one.** Enlarging is roughly a minute per megapixel, so
it tells you the size and the time before it starts, and can be cancelled. The
rest are seconds.

**Honest about the limits.** Object removal works at 512 pixels internally, so
removing a lamp post from a 12 megapixel photograph is excellent and removing a
building is not. The application says so rather than letting you find out.

---

## Your images stay yours

Nothing you open or make leaves this machine. There is no account, no telemetry
and no analytics.

The only network request InGrafiti makes is an optional check for a newer
version, which can be switched off in Preferences. Everything else - including
every one of the sixteen AI features - works with the network cable out.

---

## Keyboard

Photoshop's shortcuts: `V M L W C I J B S E G O P T U H Z` for tools,
`Shift`+letter to cycle a group, `[` and `]` for brush size, `1` to `0` for
opacity, `X` and `D` for colours, `Esc` to drop a selection, and `Ctrl+J`,
`Ctrl+T`, `Ctrl+E`, `Ctrl+G`, `Ctrl+L`, `Ctrl+M`, `Ctrl+U` and the rest.

`Ctrl+Shift+P` puts the cursor in the search bar. **Help > Keyboard Shortcuts**
lists them all, searchable.

---

## Author

**Fady Azzi**

Copyright © 2026 Fady Azzi. All rights reserved.

---

## NOTE

Some anti-virus products or EDRs might block the download of the exe file, as it
is not yet signed with a code-signing certificate. You can download the zip file
as a workaround.

Please download the latest exe or zip version from the "Releases" section on the
right, or use the direct links below.

Direct link to the exe is:
https://github.com/FadyAzzi/InGrafiti/releases/latest/download/InGrafitiInstaller.exe

Direct link to the zip is:
https://github.com/FadyAzzi/InGrafiti/releases/latest/download/InGrafitiInstaller.zip
