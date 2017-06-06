IBarcodeScan Sample
=====================

This sample project shows how to intergrate the cordova barcode scanning plugin into the main app project. Please carefully read the *package.json* file and the *config.xml* file. The former contains information about required cordova plugins (*cordova-plugin-file*, *cordova-test-framework*). The *cordova-plugin-camera* is used for taking photos.

## Using this project

You can use compiled *apk* file, install it on devices that cause problems, and then check the detection results on various photos. In general scanning multiple 1D barcodes on the one image significantly lowers the probability of detecting all codes at once. Betters results can be achieved with 2D barcodes like QR Codes or Aztec Codes (which are more resistant to image distortions).

## Running unit tests
In order to run unit test just select **Start unit tests** from the "hamburger" menu. I suggest to tap *Reset App* prior to runnint tests.
