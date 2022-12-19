# Use three.js to make a VR panorama viewer

## Install WebXR API simulator chrome plugin to simulate VR headset

https://chrome.google.com/webstore/detail/webxr-api-emulator/mjddjgeghkdijejnciaefnkjmkafnnje?hl=en

## Run `python -m http.server`

It is surprising that how secure our web browsers are versus how many computers still get infected with virus and ransomware, but the truth is that we need to set up a web server to host our assets so the browser are happy with us loading some random 3d model file and some random images as the textures.

1. Make sure you have `python` installed. If you uses a Mac, you are covered.
2. Open `Terminal` and `cd The_Folder_You_Unzipped_The_Repository_To/public`
3. Run `python -m http.server`
4. Open your browser (don't mention Internet Explorer, it is not supported), type `localhost:8000` and Voila!

To Be Continued...
