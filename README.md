# Spin
[Vimeo](https://vimeo.com/381982295)

![img](/images/img2.jpg)

## Notes

#### Modes (project path: /Spin/Modes):
* Fluid Boxes: uses the [Flex CHOP](https://github.com/vinz9) so is Windows only
* Alien Cube: uses high poly cubes, so might be slow on old gpus. shapes can also be switched if needed
* Picture Tiles: different pictures can be substituted in the "Picture Tiles" Base COMP

*Whenever choosing one of these modes, it will launch stored parameter presets found in: /Spin/mode_change.  Update stored presets by using the Snap function of the Constant CHOPs. Also more modes can be created.*

#### Grid Size:
Changing this usually requires Reset to be toggled On and Off.

#### Shape Scale:
For x,y,z scale

#### Vert/X/Horiz/Y Rotate Multiplier:
Affects how much the optical flow spins the shape. Also see Optical Flow's parameter: "flow scale"

#### Rotation Lag:
How much lag there is on the spins. Lower = more lag, slower reaction, Higher = less and quicker.

#### Snap:
You can have the shapes snap to the closest angle (ex. for cubes, it's usually 90° for a face). "Begin" means the snap will trigger after a certain number of frames of idle / no optical flow. "Time" determines how long it takes to go from current angle to snapped angle.

#### Lock:
Limits the rotation of spinning to an axis and an angle(currently max is 180°). In Picture Tiles mode, this is used to make it easier to flip all tiles to the same side without overflipping them and having them go back to the original side (so this limits rotation to just [+0° <-> +180°])

#### Optical Flow:
See [here](https://github.com/DBraun/TouchDesigner_Shared/tree/master/TOPs) for more details

![img](/images/img1.jpg)
