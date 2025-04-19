# obsidian-HarmonyOSTabletCanvasMouseScrollPatch
This is a plugin designed to address the issue where the mouse wheel cannot be used to zoom in Obsidian Canvas on HarmonyOS tablets.

On HarmonyOS tablets, the mouse scroll triggers the touchstart, touchmove, and touchend events instead of the wheel event, which prevents zooming in Canvas using the mouse. This plugin adds support for zooming in Canvas on HarmonyOS tablets by enabling Ctrl + mouse wheel.
