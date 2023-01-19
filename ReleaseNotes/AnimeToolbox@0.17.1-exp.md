```
English follows after Japanese.
```

# 更新内容

|**パッケージ名**|**更新**|**旧バージョン**|**新バージョン**|**変更履歴**|
| :-: | :-: | :-: | :-: | :-: |
|Unity|:white_check_mark:|2020.3.41f1|**Unity 2020.3.43f1**||
|HDRP||10.10.1||[変更](https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@10.10/changelog/CHANGELOG.html) |
|URP||10.10.1||[変更](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@10.10/changelog/CHANGELOG.html)|
|Cinemachine||2.8.9||[変更](https://docs.unity3d.com/Packages/com.unity.cinemachine@2.8/changelog/CHANGELOG.html)|
|Timeline||1.5.7||[変更](https://docs.unity3d.com/Packages/com.unity.timeline@1.5/changelog/CHANGELOG.html)|
|Recorder||3.0.3||[変更](https://docs.unity3d.com/Packages/com.unity.recorder@3.0/changelog/CHANGELOG.html)|
|ToonShader|:white_check_mark:|0.8.2-preview|**0.8.3-preview**|[変更](https://docs.unity3d.com/Packages/com.unity.toonshader@0.8/changelog/CHANGELOG.html)|
|SelectionGroup|:white_check_mark:|0.7.4-preview|**0.8.0-preview**|[変更](https://docs.unity3d.com/Packages/com.unity.selection-groups@0.8/changelog/CHANGELOG.html)|
|MaterialSwitch|:white_check_mark:|0.8.1-preview|**0.8.2-preview**|[変更](https://docs.unity3d.com/Packages/com.unity.material-switch@0.8/changelog/CHANGELOG.html)|
|MeshSync||0.16.2-preview||[変更](https://docs.unity3d.com/ja/Packages/com.unity.meshsync@0.16/changelog/CHANGELOG.html)|
|Streaming Image Sequence|:white_check_mark:|0.16.0-preview|**0.16.1-preview**|[変更](https://docs.unity3d.com/Packages/com.unity.streaming-image-sequence@0.16/changelog/CHANGELOG.html)|
|VisualCompositor|:white_check_mark:|0.25.1-preview|**0.26.1-preview**|[変更](https://docs.unity3d.com/Packages/com.unity.visual-compositor@0.26/changelog/CHANGELOG.html)|
|Storyboard||0.7.1-preview|||

## **ハイライト**

### **VisualCompositor**

* URP プロジェクトで、matte と depth を出力できるようにしました。

  ![](https://user-images.githubusercontent.com/71803280/213374633-a090c2cb-cf68-4044-948e-5d94612d3141.png)

* Unity プロファイラー との統合を実装しました。

  ![profiler](https://user-images.githubusercontent.com/71803280/213129643-eae056ab-2112-479e-b6a9-3e3ee316471b.png)

* 処理負荷が比較的に高いノードを赤色で囲むようにしました。

  ![](https://user-images.githubusercontent.com/71803280/213129544-233af8a2-23c2-4fff-bf77-73225d44b56c.png)

* 他のモジュールの更新が終わってから、 VisualCompositor の処理を実行するようにしました (PostLateUpdate)。

* Post Processing Stack v2 を使わないビルトインレンダーパイプラインで、MSAA を適用できるようにしました。

* URP で、MSAA を適用できるようにしました。

* SplineMaskNode の UI を一新しました。

  ![](https://user-images.githubusercontent.com/71803280/213129858-28308fec-173f-47a2-a29a-4da3b4575fc4.png)


### **MaterialSwitch**

* MaterialSwitchClipにあらゆる種類のテクスチャを適用できるようにしました。

### **SelectionGroup**

* GoQL で非アクティブのオブジェクトを検索できるようにしました。
  ```
  <active:false>
  ``` 



---

# Updates

|**Package**|**Update Status**|**Previous Version**|**New Version**|**Update History**|
| :-: | :-: | :-: | :-: | :-: |
|Unity|:white_check_mark:|2020.3.41f1|**Unity 2020.3.43f1**||
|HDRP||10.10.1||[Changes](https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@10.10/changelog/CHANGELOG.html) |
|URP||10.10.1||[Changes](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@10.10/changelog/CHANGELOG.html)|
|Cinemachine||2.8.9||[Changes](https://docs.unity3d.com/Packages/com.unity.cinemachine@2.8/changelog/CHANGELOG.html)|
|Timeline||1.5.7||[Changes](https://docs.unity3d.com/Packages/com.unity.timeline@1.5/changelog/CHANGELOG.html)|
|Recorder||3.0.3||[Changes](https://docs.unity3d.com/Packages/com.unity.recorder@3.0/changelog/CHANGELOG.html)|
|ToonShader|:white_check_mark:|0.8.2-preview|**0.8.3-preview**|[Changes](https://docs.unity3d.com/Packages/com.unity.toonshader@0.8/changelog/CHANGELOG.html)|
|SelectionGroup|:white_check_mark:|0.7.4-preview|**0.8.0-preview**|[Changes](https://docs.unity3d.com/Packages/com.unity.selection-groups@0.8/changelog/CHANGELOG.html)|
|MaterialSwitch|:white_check_mark:|0.8.1-preview|**0.8.2-preview**|[Changes](https://docs.unity3d.com/Packages/com.unity.material-switch@0.8/changelog/CHANGELOG.html)|
|MeshSync||0.16.2-preview||[Changes](https://docs.unity3d.com/ja/Packages/com.unity.meshsync@0.16/changelog/CHANGELOG.html)|
|Streaming Image Sequence|:white_check_mark:|0.16.0-preview|**0.16.1-preview**|[Changes](https://docs.unity3d.com/Packages/com.unity.streaming-image-sequence@0.16/changelog/CHANGELOG.html)|
|VisualCompositor|:white_check_mark:|0.25.1-preview|**0.26.1-preview**|[Changes](https://docs.unity3d.com/Packages/com.unity.visual-compositor@0.26/changelog/CHANGELOG.html)|
|Storyboard||0.7.1-preview|||

## **Highlights**

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


### **MaterialSwitch**
* fix: allow overriding texture properties with any texture type


### **SelectionGroup**
* feat: query active/inactive GameObjects in GoQL
  ```
  <active:false>
  ``` 

