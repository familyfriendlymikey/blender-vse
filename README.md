# Blender VSE

## Why Use Blender VSE For Video Editing?
- Intuitive & very fast workflow (with some plugins).
- Interface is very customizable.
- Can remap any hotkey, using both keyboard and mouse buttons.
- Blender's keyframing and graph editor.
- Frame accurate.
- Open source.
- Fast to open.
- Cross platform.
- Extensible.

## Why Not Use Blender VSE For Video Editing?
- Slow rendering and playback (GPU rendering WIP).
- Will not conform media.
- Small community compared to Adobe products.
	- Not many good tutorials (yet).
	- Not many transitions or preset effects or templates.
- Some quirky things that don't make sense (like images loading in at the canvas resolution).
- Not for everyone but if you like the workflow, it's great.

## Downloading 2.83.5 LTS
Download latest installer from [here](https://www.blender.org/download/lts/).

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
- Select all your strips and press "Set Selected Strip Proxy".
- Enable the proxy in the viewport (press `n` if the panel isn't there).
- Safe areas.

## Moving Shit Around
- Press `g` to move something.
- Cancel any action with right click.
- `Alt + click` video or audio to mute, or select strips and press `H`.

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
- `c` to crop a clip, `Shift + C` to make canvas same size as crop.
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

## More Hotkeys
- Press `x` or `y` to move something on a specific axis.
- Transform by typed amount.
- `a` to select all strips.
- `Alt + a` to deselect all strips.
- `l` to select group of touching strips.
- `.` key to zoom to selection.
- `b` to box select.
- `k` to cut with knife.
- `Shift + Alt + g` to select handles of cut.
- `Shift + x` to delete selection and move stuff over.
- `Ctrl + z` to undo, `Ctrl + Shift z` to redo.
- `n` to pop up right side menu menu. `p` to bring up left side menu.
- `x` to interactive cut.
- `Backspace` to remove gaps natively.
- `c` to concatenate selected strips to the left.
- `Shift + c` to concatenate all strips in channel to the left.
- `Shift + S` to bring SELECTION to cursor.
- `Ctrl` while moving a strip to snap.
- Hold `Shift` during a transform to be precise.
- `d` to duplicate strips.
- `Ctrl + Alt + p` to set render region to selection.
- `Right Click` an option with many strips selected > `apply to selected` to apply that value to all selected strips.
- `Up/Down arrow` will move to nearest keyframes.
- `Home` key will zoom your project to fit the view.
- `Something` will crossfade the selected strips. Make sure you don't include audio.

## Misc
- Meta strips give some unique transform workflows.
- You can do math in input boxes.
- You can copy and paste an input box without clicking.
- Color management panel supports sRGB and raw.
- Speed up footage, gaussian blur.

## BPSProxy
- Installing and running BPSProxy.

## My Current Hotkey Settings
- Frame by frame movement with `z` and `x`.
- `Right click` to move playhead around on timeline.
- `Alt + Mouse Button 4` to soft cut under cursor.
- `Alt + Mouse Button 5` to hold cut selected strips.
- `w` and `s` to move clip up or down.
- Playhead limited to frame range.
- I have renders set to go to the image editor instead of a separate window.
- I set undo tree to really far.
- `Shift z` to interactive cut.
- `Middle Mouse 4/5` move to beginning and end of strip.

## Masking
- Strip mask.
- Guassian blur, must use transform strip.
- Its just a preview.
- feather, switch.
