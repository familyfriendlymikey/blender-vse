# Blender VSE

## Why Use Blender VSE For Video Editing?
- Intuitive & very fast workflow (with some plugins).
- Interface is very customizable.
- Can remap any hotkey, using both keyboard and mouse buttons.
- Blender's keyframing and graph editor.
- Frame accurate.
- Open source and free.
- Fast to open.
- Cross platform.
- Extensible.

## Why Not Use Blender VSE For Video Editing?
- Slow rendering and playback (GPU rendering WIP).
- Will not conform media.
- Small community compared to Adobe products.
	- Not many good tutorials (yet).
	- Not many transitions or preset effects or templates.
- A little buggy sometimes.
- Not for everyone but if you like the workflow, it's great.

## Downloading Blender
- Download latest release [here](https://www.blender.org/download/).
- Download LTS [here](https://www.blender.org/download/lts/).

## Note
A lot of blender's hotkeys work in any portion of the program.
For example, `a` to select all works in the timeline, in the keyframe view, in the 3D view, and more.

## UI Navigation
- Create a Video Editing workspace by pressing plus at the top.
- Middle mouse button drag to move stuff around.
- Scroll wheel zooms in and out.

## Adding Media
- Add multiple videos/images with `Shift + A`.
- Press `y` on an image strip to split into separate images.

## Generating Proxy
- Disable cache.
- Generate the proxy.
- Select all your strips and press "Set Selected Strip Proxy". This will do so for all selected strips.
- Enable the proxy in the viewport (press `n` if the panel isn't there).
- Safe areas.

## Moving Shit Around
- Press `g` to move something.
- Cancel any action with right click.
- `H` to mute strips.

## Splitting A Strip
- Hold offset: extending last frame, reversing clips and such.
- Blender pushes strips to end if you place on top.

## Rendering
- Render frame with `F12`. This will not save your image anywhere.
- To save an image, go to the render and click `Image > Save`.
- Choose an output folder in the render panel.
- Render the frame range with `Ctrl + F12`.
- Relative render path.
- Mediainfo framerate.

## Customizing Interface
- Remove panels by clicking on their corner.
- You can drag sections you never use elsewhere.
- `Ctrl + Middle Mouse Click Drag` to change the size of the timeline.
- Set a default start up file will do EXACTLY as you say.

## Installing Plugins
Install [VSE Transform Tools](https://github.com/doakey3/VSE_Transform_Tools/releases) and Power Sequencer.

## Adding More Media
- Enable offset to add something that isn't the canvas resolution.
- Click audio, display waveform, change volume.
- Blending modes.
- Shit on top channel takes visual precedence.
- A/V Sync menu: `Timeline > Playback`.

## Using VSE Transform Tools
- `g`, `s`, and `r` to move, scale, and rotate selected elements.
- `Alt + r/s/v` to reset.
- `c` to crop a clip, c to confirm, `Shift + C` to make canvas same size as crop.
- Changing pivot point with `Ctrl + click`.
- Right click to cancel ANY action.

## Animating Stuff
- You can really animate any value.
- It's easiest to animate with the auto keyframe option enabled.
- Graph editor.
- Default is bezier, `t` to change selected.
- In graph editor, `v` to change handle type.

## Scenes
- Full copy scene.
- Copying between scenes.
- Appending scenes from other file.

## Other Strip Types and Options
- adding text
- speed control
- gaussian blur
- color strip
- transitions
- reverse strips
- ctrl g make meta strip, ctrl alt g remove it, tab to enter and exit
- `Right Click` an option with many strips selected > `apply to selected` to apply that value to all selected strips.

## More Hotkeys

### Selection
- `a` to select all strips.
- `Alt + a` to deselect all strips.
copy and paste with ctrl c and ctrl v, paste will paste at playhead, ctrl x to cut
Shift to multiselect
ctrl left mouse to select evcerying on side of playhead
`Ctrl + Click` Selects related strips
- `Shift + Alt + g` to select handles of cut.
- `l` to select group of touching strips.

### Moving
shift to do ANYTHING slowly
ctrl key snap depends on which side of the selection your mouse is on
alt right and left to swap ACTIVE strip
- Press `x` or `y` to move something on a specific axis.
- Transform by typed amount.
- `e` with the playhead on the strip on a side of the playhead to grab strip side, alt + click to ripple edit
- `c` to concatenate selected strips to the left.
- `Shift + c` to concatenate all strips in channel to the left.
- `Shift + S` to bring SELECTION to cursor.
- `d` to duplicate strips.

### Navigation
numpad . to view selection (emulate numpad option)
home to zoom to render range + strip range
- `Ctrl + z` to undo, `Ctrl + Shift z` to redo.
- `Up/Down arrow` will move playhead to nearest keyframes.

### Cutting, Trimming, Editing
alt k control k to trim either side, + shift will ripple
- `k` to cut with knife.
- "Trim" shift t
- `Shift + x` to CUT selection and ripple.
- f to fade strip in and out, ctrl f to fade in only, alt f to fade out only, ctrl alt f to remove fade

### View 
- `n` to pop up right side menu menu. `t` to bring up tools menu.
- toggle waveforms alt w
- `Ctrl + Alt + p` to set render region to selection.

## Misc
- Meta strips give some unique transform workflows.
- You can do math in input boxes.
- You can copy and paste an input box without clicking.
- Color management panel supports sRGB and raw.

## BPSProxy
- Installing and running BPSProxy.

## My Current Hotkey Settings
In order to remap something in blender, you have to delete all conflicts.

Searching keymap for both input and name.

- `Animation > Change Frame: Sequencer Tool: Select Box` -> `Right Click`
- `Sequencer: Mouse Trim > T`, Time Cursor, Remove Gaps.
	- Uncheck `SequencerCommon > Context Toggle`
- `Sequencer: Split Strips Under Cursor: Mouse Button 5`
- `Sequencer: Trim Left Or Right Handles: Mouse Button 4` Left, Ripple.
- `Frames: Frame Offset > z, x`
- `Sequencer: Channel Offset > w, s`
	- Uncheck `SequencerCommon: Set Tool By Name`
- `Sequencer: Frame Selected > tilde`

## Preferences

## Other Settings
- `Bottom Left Timeline Menu, Playback > AV Sync, Limit Playback to Frame Range`

- "Go To Current Frame"
- "Jump To Strip"
- Playhead limited to frame range.
- I have renders set to go to the image editor instead of a separate window.
- I set undo tree to really far.

## Color Grading

## Masking
- Strip mask.
- Guassian blur, must use transform strip.
- Its just a preview.
- feather, switch.

### Other Hotkeys
- `Something` will crossfade the selected strips. Make sure you don't include audio.
- `Backspace` to remove gap natively, `Shift Backspace` to remove all gaps natively.
- f9 to change props of thing you just did.
- crossfade ctrl alt c SELECT ONCE, ctrl alt f to delete
