# Augmented Reality Investment Project

* **awe.js** - AR demo projecting a geometric shape over QR code. 3-D model (.obj) also imported, but the scale/position needs to be fixed.

* **2D UI Display** - Unity Project for showing UI when image (artargetimage.jpg) is detected. 

* **AR_1_notes.xlsx** - Notes on tasks and useful links 

* **jsfeat_demo** - Potential object/feature tracking js library for web browser AR application development
    - If index.html is not running properly, see below to launch Google Chrome with permissions
    - After allowing webcam to run in your browser, click "train_pattern" in the menu to analyze object/feature match
    - Images can be added in jsfeat_demo/resources 
    - Ensure the image tag is updated with the relevent image file in index.html

*If you are having trouble seeing images/webcam stream, you may need to launch Chrome to allow external file access...*
1. Close out all chrome instances
2. Launch cmd
3. Launch chrome using path and access tag (ex: C:\Users\593457\AppData\Local\Google\Chrome\Application\chrome.exe --allow-file-access-from-files)
4. Navigate to webpage using the local path
