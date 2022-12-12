**Updates**
========


|**Package**|**Update Status**|**Previous Version**|**New Version**|**Update History**|
| :-: | :-: | :-: | :-: | :-: |
|Unity|**Available**|2020.3.39f1|**Unity 2020.3.41f1**||
|HDRP|**Available**|10.9.0|**10.10.1**|[Changes](https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@10.9/changelog/CHANGELOG.html) |
|URP|**Available**|10.9.0|**10.10.1**|[Changes](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@10.9/changelog/CHANGELOG.html)|
|Cinemachine|No update|2.8.9||[Changes](https://docs.unity3d.com/Packages/com.unity.cinemachine@2.8/changelog/CHANGELOG.html)|
|Timeline|No update|1.5.7||[Changes](https://docs.unity3d.com/Packages/com.unity.timeline@1.5/changelog/CHANGELOG.html)|
|Recorder|No update|3.0.3||[Changes](https://docs.unity3d.com/Packages/com.unity.recorder@3.0/changelog/CHANGELOG.html)|
|ToonShader|No update|0.8.2-preview||[Changes](https://docs.unity3d.com/Packages/com.unity.toonshader@0.8/changelog/CHANGELOG.html)|
|SelectionGroup|No update|0.7.3-preview||[Changes](https://docs.unity3d.com/Packages/com.unity.selection-groups@0.7/changelog/CHANGELOG.html)|
|MaterialSwitch|**Available**|0.7.4-preview|**0.8.1-preview**|[Changes](https://docs.unity3d.com/Packages/com.unity.material-switch@0.7/changelog/CHANGELOG.html)|
|MeshSync|**Available**|0.15.0-preview|**0.16.2-preview**|[Changes](https://docs.unity3d.com/ja/Packages/com.unity.meshsync@0.14/changelog/CHANGELOG.html)|
|Streaming Image Sequence|No update|0.16.0-preview||[Changes](https://docs.unity3d.com/Packages/com.unity.streaming-image-sequence@0.15/changelog/CHANGELOG.html)|
|VisualCompositor|**Available**|0.24.2-preview|**0.25.1-preview**|[Changes](https://docs.unity3d.com/Packages/com.unity.visual-compositor@0.23/changelog/CHANGELOG.html)|
|Storyboard|No update|0.7.1-preview|||

## **Highlights**
### **MaterialSwitch**
- Added a button to MaterialSwitchClip to allow color to be loaded from materials. 
- Updated MaterialPropertyNameRemapEditor layout.
- ![](UAT_017.png)MaterialSwitchClip property name can now be displayed to artists under a different name. (Material Property Name Remap)
###
### **MeshSync**
- Key frames can now be adjusted with a workflow that uses SceneCache. 
- Materials are now supported. 
- Added server update tracking. 
- Added feature to automatically delete child objects during the next sync session without notifying the user.
- Script callbacks from Unity can now be inserted. 
- Added a button to display the plugin folder from Preferences.

### **VisualCompositor**
-
  ![UAT_018](https://user-images.githubusercontent.com/2647923/206109000-0e35c50b-4c4e-4798-a929-4906ac66be97.png)
- 【New Feature】 Added MaterialIDRenderNode, which renders each material ID in a different color.  

  ![UAT_019](https://user-images.githubusercontent.com/2647923/206109049-223e24f5-449c-44b2-995a-9024a25db5ad.png)
- 【New Feature】 Added ObjectIDRenderingNode, which renders each object in a different color. 
- 【New Feature】 Added PlayableDirectorTimeNode.

  ![UAT_020](https://user-images.githubusercontent.com/2647923/206109109-dbab662a-909e-40b4-ad23-3ccff2343da1.png)
- 【New Feature】Added a node group for calculations.

  ![UAT_021](https://user-images.githubusercontent.com/2647923/206109138-2b05daf9-a892-423d-be75-c19d2d3045f4.png)
- 【New Feature】 Added a snapshot feature.
 
  ![UAT_022](https://user-images.githubusercontent.com/2647923/206109189-99e59efd-3f7b-4647-b73b-0cfa28a402ba.png)
- Improved the BlurNode feature to allow for radius settings, directional blur, etc.
- CoherentNoiseNode now supports Timeline. 
- DropShadowNode now supports Timeline. 
- Changed value node and render state node icons to make them more visible. 
- Points can now be deleted in the SplineMaskEditorWindow from the context menu.
