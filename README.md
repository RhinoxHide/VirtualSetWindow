# Movie Making in Games Engines Project Repository

|  General Info  | |
| ---|---|
| Working Title | Virtual Set Window Plug-In |
| Final Title | Virtual Set Window Plug-In |
| Student | Benedikt Walter, benedikt.walter1@stud-mail.uni-wuerzburg.de, s357590<br />Fabian Kirchen, kontakt@fabiankirchen.com, fabiankirchen.com |
| Target Platform(s) | `Unreal Engine 4` |
| Start Date | 05.11.2020 |
| Study Program | Games Engineering B.Sc., JMU Würzburg <br />Kommunikationsdesign, FHWS |

## Abstract

Virtual Set PlugIn gives users a window into a virtual world for virtual production. 
To create a realistic looking winow, we made this plug-in that simulates a window effect. 

## Wiki Links

- [**Documentation**](https://gitlab2.informatik.uni-wuerzburg.de/GE/Teaching/special-courses/2020-movie-making-with-game-engines/projects/03-movie-making/-/wikis/Documentation)
- [**Manual**](https://gitlab2.informatik.uni-wuerzburg.de/GE/Teaching/special-courses/2020-movie-making-with-game-engines/projects/03-movie-making/-/wikis/Manual)


## How to install and use the virtual set window plugin.

- Move the plugin folder "virtualsetwindow" into your unreal plugin folder. On Windows it is normally located under `C:\Program Files\Epic Games\UE_x.xx\Engine\Plugins\VirtualProduction`.

- Open or create your unreal project.

- Go to Edit – Plugins, activate Virtual Set Window and restart unreal engine.

- Open "virtualsetwindow Content" in the content browser of your project. Move VSW_Image, VSW_Screen and VSW_Tracker into your scene. Attach VSW_Image and VSW_Tracker to your tracker object. VSW_Screen has to have the same coordinates as your tracker. Give VSW_Tracker the coordinates 0, 0, 0 and VSW_Image the x coordinate of 700 relative to your tracker.

- Open the level blueprint and set it up as shown. You can find the reference to VSW_Screen easily if you've selected it before opening the level blueprint. To find "Set View Target with Blend" you have to uncheck "Context Sensitive"



