---
ns: GRAPHICS
aliases: ["0x3669F1B198DCAA4F"]
---
## DISABLE_OCCLUSION_THIS_FRAME

```c
// 0x3669F1B198DCAA4F 0x0DCC0B8B
void DISABLE_OCCLUSION_THIS_FRAME();
```


This disables occluders that are under the map or inside buildings and prevents the 'flickering' rendering when inside a building with no interior or under the map. This needs to be called every frame.
