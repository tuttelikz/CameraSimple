# Simple Camera intent

<img src="./Screenshots/camera_demo.gif" width="300">

## Procedure:

1. Define `CAMERA`, `WRITE_EXTERNAL_STORAGE` permissions and camera feature in `Manifest`
2. Define `ImageView` and `Button` in layouts
3. Initiate runtime permissions for camera and external storage
4. Handle permissions with `onRequestPermissionsResult()`
5. Define `openCamera()` (camera intent) method
6. Set URI of `ImageView` resource  after successful return from Camera intent