Android-for-Python
==================

*Kivy Examples that will build for Android.*

**Example**, *noun*
 - one that serves as a pattern to be imitated or not to be imitated
 - a parallel or closely similar case especially when serving as a precedent or model

Each repository (other than the Users Guide) contains a stand alone runnable example. All examples run on Android, most on a desktop, and a few on iOS.

A buildozer.spec is included or the required modifications to buildozer.spec are documented.

### [Android-for-Python-Users](https://github.com/Android-for-Python/Android-for-Python-Users)

An unofficial Users' Guide.

### Cloud Storage Examples

[Overview](https://github.com/Android-for-Python/cloud_storage_examples)

#### [Firestore Example](https://github.com/Android-for-Python/cloud_storage_examples/tree/main/rest_firestore_example), it depends on [firestore4kivy](https://github.com/Android-for-Python/firestore4kivy). Runs on desktop, Android, and iOS.
 
#### [Pyrebase4 Example](https://github.com/Android-for-Python/cloud_storage_examples/tree/main/pyrebase4_example), it depends on [Pyrebase4](https://github.com/nhorvath/Pyrebase4). Runs on desktop, and Android.

####[Firebase-admin Example](https://github.com/Android-for-Python/cloud_storage_examples/tree/main/firebase_admin_example), it depends on [firebase-admin](https://firebase.google.com/docs/admin/setup/). Firebase-admin is a security risk if available to un-trusted users. Runs on desktop, and Android.

### BroadcastReceiver Examples

Android *only* examples of using the Python class `android.broadcast.BroadcastReceiver`.

#### [Overview](https://github.com/Android-for-Python/BroadcastReceiver_examples)

#### [WiFi_scanner_example](https://github.com/Android-for-Python/BroadcastReceiver_examples/tree/main/WiFi_scanner_example)

#### [Bluetooth_scanner_example](https://github.com/Android-for-Python/BroadcastReceiver_examples/tree/main/Bluetooth_scanner_example)

### Speech Examples

#### [speech_recognizer_example]()

### Camera Examples

#### [c4k_photo_example](https://github.com/Android-for-Python/c4k_photo_example)

A [Camera4Kivy](https://github.com/Android-for-Python/Camera4Kivy) Preview widget example. Illustrates basic layout orientation, aspect ratio, and letterbox handling, on multiple screens. Basic camera functionality including photo capture, screenshot capture, and on Android capture of video with audio. 

#### [c4k_qr_example](https://github.com/Android-for-Python/c4k_qr_example)

A [Camera4Kivy](https://github.com/Android-for-Python/Camera4Kivy) Preview widget example. Everything you need to read a restaurant menu. Long press or double click on a highlighted QR code to open a web browser. Illustrates basic analysis, screen annotation, and user interaction.

#### [c4k_opencv_example](https://github.com/Android-for-Python/c4k_opencv_example)

A [Camera4Kivy](https://github.com/Android-for-Python/Camera4Kivy) Preview widget example. Edge detect the video stream. Illustrates using OpenCV analysis and replacing the original preview with the transformed image.

#### [c4k_mlkit_example](https://github.com/Android-for-Python/c4k_mlkit_example)

A [Camera4Kivy](https://github.com/Android-for-Python/Camera4Kivy) Preview widget example. Face detect, MLKit is Android only. Illustrates using the ImageProxy api.

#### [c4k_tflite_example](https://github.com/Android-for-Python/c4k_tflite_example)

A [Camera4Kivy](https://github.com/Android-for-Python/Camera4Kivy) Preview widget example. Object classification. Illustrates using a large Tensorflow Lite model, and writing text to the Preview image. Does not (yet?) run on Android.

### Service Example

#### [Multi-Service-Example](https://github.com/Android-for-Python/Multi-Service-Example)

Schedule tasks on one or more Android services, foreground or background.

### Common Getsures Example

#### [Common-Gestures-Example](https://github.com/Android-for-Python/Common-Gestures-Example)

Pan, zoom, long press, and friends.

### Shared Storage Examples

#### [shared_storage_example](https://github.com/Android-for-Python/shared_storage_example)

Copy to and from shared storage on Android 5 and above devices, using [androidstorage4kivy](https://github.com/Android-for-Python/androidstorage4kivy).

#### [share_send_example](https://github.com/Android-for-Python/share_send_example).

Share a file or plain text with another app, using [androidstorage4kivy](https://github.com/Android-for-Python/androidstorage4kivy). 

#### [share_receive_example](https://github.com/Android-for-Python/share_receive_example)

Recieve a Share from another app, using [androidstorage4kivy](https://github.com/Android-for-Python/androidstorage4kivy).

### Viewer Examples

#### [Webview-Example](https://github.com/Android-for-Python/Webview-Example)

Accepts https:// and file:// urls. Full screen, dismiss with back gesture or back button. 

#### [PDFview-Example](https://github.com/Android-for-Python/PDFview-Example)

Accepts .pdf files. Full screen, dismiss with back gesture or back button.





