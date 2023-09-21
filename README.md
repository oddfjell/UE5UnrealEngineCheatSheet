# UnrealEngineCheatSheet

Many of the shortcuts is written on the buttons in the UI, so I will not write all of them here <br>
Example: <br> ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/6c9e774e-2e9a-40b1-9c86-40fe3683c380) <br>
**YOUTUBE TUTORIAL:** [▶️](https://www.youtube.com/watch?v=k-zMkzmduqI)

## User interface
| Command | Control |
| -- | -- |
| Content Drawer | `CTRL` + `SPACE` |
| Dock Windows | `F10` |

## Movement
| Command | Control |
| -- | -- |
| Movement | `W A S D Q E` |
| Rotate Camera | `Right Mouse Button` |
| Adjust Camera Speed | (`Right Mouse Button` or `Left Mouse Button`) + `Mouse Wheel` |
| Focus to Object | Toggle object in the outliner or the viewport + `F` |
| Pivot Object | `ALT` + `Left Mouse Button` |
| Zoom In and Out Object | `ALT` + `Right Mouse Button` |

## Viewport Settings
| Command | Control |
| -- | -- |
| Wireframe Movement | `Right Mouse Button` + Move the Mouse |
| Wireframe Zoom | `Mouse Wheel` |
| Game View | `G` |

![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/56154309-471c-47a3-abb6-dc90b1545f1b)


## Moving and Creating Objects
| Command | Control |
| -- | -- |
| Select Objects | `Q` |
| Select and Translate Objects | `W` |
| Select and Rotate Objects | `E` |
| Select and Scale Objects | `R` |
| Turn On and Off Translation Snapping | ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/4bd0647e-f6cb-4104-8161-d2f998ff80e1) ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/32f8a724-5c5a-430b-8b1b-736f150af92e) |
| Translation Snapping Size | Press the number beside the grid and choose how many cm |
| Turn On and Off Rotation Snapping | ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/d802e287-b2e1-4af4-86f9-d90d4869d3db) ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/89d37d5e-03d8-49e9-a8e4-9de0c543ea36) |
| Rotation Snapping Size | Press the number beside the angle and choose how many degrees |
| Turn On and Off Scale Snapping | ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/7845c873-a15d-4045-a2be-5950c571cc04) ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/a10b979a-a8fb-4832-9494-3bea9e5b7109) |
| Scale Snapping Size | Press the number beside the arrow and choose the ratio |
| Move Object in Direction of the World (Globally) | ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/f6dcf279-dde2-42c8-a254-8d3f84edc3ea) |
| Move Object in Direction of the Object (Locally) | ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/21ead833-89bd-4937-b841-3f27d4b22007) |
| Duplicate Object | `CTRL` + `D` |
| -- | `ALT` + Drag (in translate mode) |
| Add Object | ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/43e04aef-654f-48aa-99f8-bec8c5182326) |
| -- | `Content\StarterContent\Props` + drag an object out with `Left Mouse Button` |
| Select Multiple Objects | `SHIFT` + Click |
| Deselect | `CTRL` + Click |
| Lock Camera to Object | `SHIFT` + Drag |
| Snap to Floor | `END` |

## Post Process and Camera Exposure
| Command | Control |
| -- | -- |
| Duplicate Map | Select Map + `CTRL` + `D` |
| Adjust Brightness | Lit -> Uncheck Game Settings -> Change EV100 |
| Quit Game | `ESC` |
| PostProcressVolume File | ‼️Too Much Stuff to Write Here‼️ |
| PostProcressVolume Globally | `Details` -> `Post Process Volume Settings` -> `Infinite Extent (Unbound)` |
| Brightness | `Details` for PostProcessVolume -> `Exposure` |

You can add any missing volumes via ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/43e04aef-654f-48aa-99f8-bec8c5182326) and select Volumes

## Intro to Materials 
| Command | Control |
| -- | -- |
| Show Engine Folder | `CTRL` + `SPACE` -> `Settings` -> `Show Engine Content` |
| Material | `CTRL` + `SPACE` -> `Content\StarterContent\Materials` -> Drag on object |
| Edit Material | `Dobble Click` on the material |

![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/2349f8f2-bbf0-4156-9981-e5c406d9c6b7)


## PBR Explained
| Command | Control |
| -- | -- |
| Find the Used Material | Click on object -> `Details` -> `Dobble Click` on the material |
| Find the Used Material | Click on object -> `Details` -> `Click` on browse to file |
| Rotate Sun | `CTRL` + `L` |
| LinearInterpolate | `L` + `Click` |
| Constant3Vector | `3` + `Click` |
| Constant Scalar | `1` + `Click` |

## Textures
| Command | Control |
| -- | -- |
| Multiply | `M` + `Click` |
| Remove Edge in Graph | `ALT` + `Click` on edge |
| -- | `ALT` + `Click` on node to remove all edges |
| Move Edge | `CTRL` + Drag |

For colour textures --> sRGB turned on <br>
For everything else --> sRGB turned off <br>
Normalmap --> Compression --> Compression Settings -- > Normalmap<br>
**Example on how to change a materials texture:**<br>

![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/9a89d9d7-3d5d-43d9-a017-321042571955)

## Material Parameters and Instances
| Command | Control |
| -- | -- |
| Convert to Parameter | `Right Click` on Constant -> Convert to Parameter |
| Constant Parameter | `S` + `Click` |

**Edit in real time by making an Material Instance and change the values of the parameters** <br>
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/f188ece1-bcc1-4e74-bd28-8aebbe264c68) <br>
**In Material Instance** <br>
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/a09c6cbf-62b0-4092-8247-5ff36dd61096)

## Create a Master Material
Create many basic parameters <br>
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/5bdd8127-fdef-4c6d-a8f2-940c84e2e7d6)

## Import/Create a Static Mesh
Create an Master Material <br>
Create an Material Instance and fix the parameter values <br>
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/88d9e84e-a4aa-4b7a-a191-b83ad5da0fc1) <br>
Create an Static Mesh and change the Material Slot <br>
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/74069140-36f4-4351-ab5e-8f255d4ab75e)  <br>

FBX Import Options
- Reset to default
- Do Not Create Material
- `Uncheck` Import Textures

Roughness and Metallic on same map: <br>
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/c0721617-7ce5-49bb-89e4-769245ee82a3)

## Move Assets Between Projects
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/ccf3ec07-fa3f-4a7d-a530-0abb76957d0a)
Migrate into the content folder

## Lighting with Lumen!
| Command | Control |
| -- | -- |

Light -> Transform -> Static

Ray tracing entire level -> Build -> Build All Levels
(creates light map)
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/a2296c4e-c63c-4768-92ce-1144c49736c6)
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/4bd51d56-e145-4736-a8a0-9d634331e50e)
Creates static map, so not good

Remove lightmap -> Windows -> World Settings -> Lightmass -> `Check` Force No Precomputated Lighting **then** Build -> Buils All Levels

Light -> Movable **then** PostProcessVolume -> Global Illumination -> Lumen
![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/63f1aabe-0fb5-4bb6-bf21-f8c633099efa)

Light -> Light -> Increase the `Source Radius`to get softer shadows








## Types of Lights
| Name | Information |
| -- | -- |
| Point Light | Emits light in all directions |
| -- | Intensity |
| -- | Source Radius |
| -- | Temperature |
| -- | Light Colour |
| -- | Indirect Lighting Intensity |
| Spot Light | Emits light in a cone |
| -- | Same settings as Point Light |
| -- | Rotate |
| -- | Outer Cone Angle -> Alters the cones "steepness" |
| -- | Inner Cone Angle -> Alters the lights falloff |
| Rect Light | Emits light in a rectangle |
| -- | Same settings as Point Light |
| -- | Rotate |
| -- | Source Width |
| -- | Source Height |
| -- | Barn Door Angle ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/ccb1cd6c-a58f-4df1-a951-ce9036a4f619) ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/6fe4d73f-26b6-4faa-a518-91bb0e7fbe50) |
| -- | Barn Door Height ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/587ce3fb-94dc-4eab-a5d8-4c7173eee910) |
| Directional Light | Sun light |
| -- | Source Angle not radius |
| Sky Light | Sun light |
| -- | Needs sky -> Add object -> Visual Effects -> Sky Atmosphere|
| -- | The sky needs directional light |
| Remove noice | PostProcessVolume Settings -> Global Illumination -> Lumen Global Illumination -> Final Gather Quality (gpu cost) |



Light not working? -> Turn off and on Affects World 


# Archviz Lighting Lumen
| Command | Control |
| -- | -- |
| Exponential Height Fog | Add object -> Visual Effects -> Exponential Height Fog |
| -- | Start Distance -> fog will not start until it is x cm away from camera  |
| Soft shadows to smaller objects | PostProcessVolume Settings -> Global Illumination -> Lumen Global Illumination -> Lumen Scene Detail ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/3d5e65e9-ae52-4f49-81d9-8608fc899d07) ![image](https://github.com/oddfjell/UnrealEngineCheatSheet/assets/99129702/6fb1bd50-a3c1-4b04-b015-5c2871561edb) |
| Manually change light | Lens -> Exposure -> `Check` Metering Mode and choose Manuel|
| -- | Exposure Compensation -> Around 13.25 is the normal|
| -- | Back to Bloom -> Can increase the Intensity|

# Archviz Lighting Baked
more preformance friendly
| Command | Control |
| -- | -- |








Set lights as moveable with lumen















## Naming Conventions
| Command | Control |
| -- | -- |
| Material | M_... |
| Material Instance | MI_... |
| Texture | T_... |
| Static mesh (3D objects) | SM_... |

