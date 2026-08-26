# Media3 Transformer Video Editor Lab

Original Android video-editing lab built around **Media3 Transformer 1.10.1**.

## Workflow
1. Pick a local video with the Storage Access Framework.
2. Choose mute, 90° rotation and scale percentage.
3. Export asynchronously to the app-specific Movies directory.
4. Observe progress and cancel an active export.

The lab uses `EditedMediaItem`, `Effects`, `ScaleAndRotateTransformation`, `Transformer.Listener` and `ProgressHolder`. Output is MP4; actual codec/effect support depends on device codecs and input format.
