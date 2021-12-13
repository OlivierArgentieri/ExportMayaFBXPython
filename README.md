# ExportMayaFBXPython
Export Maya FBX Python with frame range

```py
import maya.cmds as cmds

cmds.FBXExportSplitAnimationIntoTakes("-clear")
cmds.FBXExportSplitAnimationIntoTakes("-v", 'toto', 1, 15)
cmds.FBXExport("-f", 'D:/ouimaya.fbx', "-s")
```
