English follows after Japanese.

# 更新内容

|**パッケージ名**|**更新状況**|**旧バージョン**|**新バージョン**|**変更履歴**|
| :-: | :-: | :-: | :-: | :-: |
|Unity|**更新あり**|2020.3.41f1|**Unity 2020.3.43f1**||
|HDRP|更新なし|10.10.1||[変更](https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@10.10/changelog/CHANGELOG.html) |
|URP|更新なし|10.10.1||[変更](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@10.10/changelog/CHANGELOG.html)|
|Cinemachine|更新なし|2.8.9||[変更](https://docs.unity3d.com/Packages/com.unity.cinemachine@2.8/changelog/CHANGELOG.html)|
|Timeline|更新なし|1.5.7||[変更](https://docs.unity3d.com/Packages/com.unity.timeline@1.5/changelog/CHANGELOG.html)|
|Recorder|更新なし|3.0.3||[変更](https://docs.unity3d.com/Packages/com.unity.recorder@3.0/changelog/CHANGELOG.html)|
|ToonShader|更新なし|0.8.2-preview||[変更](https://docs.unity3d.com/Packages/com.unity.toonshader@0.8/changelog/CHANGELOG.html)|
|SelectionGroup|**更新あり**|0.7.4-preview|**0.8.0-preview**|[変更](https://docs.unity3d.com/Packages/com.unity.selection-groups@0.8/changelog/CHANGELOG.html)|
|MaterialSwitch|**更新あり**|0.8.1-preview|**0.8.2-preview**|[変更](https://docs.unity3d.com/Packages/com.unity.material-switch@0.8/changelog/CHANGELOG.html)|
|MeshSync|更新なし|0.16.2-preview||[変更](https://docs.unity3d.com/ja/Packages/com.unity.meshsync@0.16/changelog/CHANGELOG.html)|
|Streaming Image Sequence|**更新あり**|0.16.0-preview|**0.16.1-preview**|[変更](https://docs.unity3d.com/Packages/com.unity.streaming-image-sequence@0.16/changelog/CHANGELOG.html)|
|VisualCompositor|**更新あり**|0.25.1-preview|**0.26.0-preview**|[変更](https://docs.unity3d.com/Packages/com.unity.visual-compositor@0.26/changelog/CHANGELOG.html)|
|Storyboard|更新なし|0.7.1-preview|||

## **ハイライト**

### **SelectionGroup**
* feat: query active/inactive GameObjects in GoQL
  ```
  <active:false>
  ``` 

### **MaterialSwitch**
* fix: allow overriding texture properties with any texture type

### **VisualCompositor**

* feat: enable RenderingNode to output depth in URP projects
* feat: enable RenderingNode to output matte in URP projects

* feat: profiler integration

  ![profiler](https://user-images.githubusercontent.com/71803280/213129643-eae056ab-2112-479e-b6a9-3e3ee316471b.png)
 
* feat: color node border based on relative performance  

  ![](https://user-images.githubusercontent.com/71803280/213129544-233af8a2-23c2-4fff-bf77-73225d44b56c.png)

* change: set the execution order of VisualCompositor to PostLateUpdate

* fix: apply AntiAliasing in built-in/URP projects without PostProcessing

* fix: apply the window and image scale properly in SplineAssetEditorWindow UI

  ![](https://user-images.githubusercontent.com/71803280/213129858-28308fec-173f-47a2-a29a-4da3b4575fc4.png)


* feat: allow users to use custom icons for nodes
  ```
  [CompositorNode("MenuTitle", "Documentation string", icon:"Assets/my-custom-icon.png")]
  public class MyCustomNode : CompositorNode
  {
    ...
  }
  ```



---

# Updates

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
- MaterialSwitchClip property name can now be displayed to artists under a different name. (Material Property Name Remap)

  ![](https://user-images.githubusercontent.com/71803280/208083909-9ad47280-649c-439d-bc1a-10dee54a6cef.png)
 
### **MeshSync**
- Key frames can now be adjusted with a workflow that uses SceneCache.
- Materials are now supported.
- Added server update tracking.
- Added feature to automatically delete child objects during the next sync session without notifying the user.
- Script callbacks from Unity can now be inserted.
- Added a button to display the plugin folder from Preferences.

### **VisualCompositor**

- 【New Feature】 Added MaterialIDRenderNode, which renders each material ID in a different color.
  ![UAT_018](https://user-images.githubusercontent.com/2647923/206109000-0e35c50b-4c4e-4798-a929-4906ac66be97.png)

- 【New Feature】 Added ObjectIDRenderingNode, which renders each object in a different color.
  ![UAT_019](https://user-images.githubusercontent.com/2647923/206109049-223e24f5-449c-44b2-995a-9024a25db5ad.png)
 
- 【New Feature】 Added PlayableDirectorTimeNode.
  ![playable-director-time-node](https://user-images.githubusercontent.com/71803280/208084780-c7c76527-8df2-40a6-9265-4b1f528df42b.png)

- 【New Feature】Added a node group for calculations.

  ![smoothstep-value-node](https://user-images.githubusercontent.com/71803280/208085041-0983908a-103b-4689-9bdb-9f51cfc62b62.png)

- 【New Feature】 Added a snapshot feature.

  ![UAT_021](https://user-images.githubusercontent.com/2647923/206109138-2b05daf9-a892-423d-be75-c19d2d3045f4.png)

- Improved the BlurNode feature to allow for radius settings, directional blur, etc.

  ![UAT_022](https://user-images.githubusercontent.com/2647923/206109189-99e59efd-3f7b-4647-b73b-0cfa28a402ba.png)
 
- CoherentNoiseNode now supports Timeline.
- DropShadowNode now supports Timeline.
- Changed value node and render state node icons to make them more visible.
- Points can now be deleted in the SplineMaskEditorWindow from the context menu.


