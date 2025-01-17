# Expo Camera Barcode Scanner Intermittent Failure

This repository demonstrates a bug in Expo's Camera component where the barcode scanner intermittently fails to detect barcodes, particularly after significant lighting changes or upon initial camera load. The `onBarCodeScanned` callback is not triggered in these instances, even when barcodes are clearly visible.

## Bug Reproduction

The `bug.js` file contains the problematic code that reproduces the issue.  Run this code and observe that barcodes might not always be scanned reliably.

## Solution

The `bugSolution.js` file provides a possible solution that involves adding additional error handling and potentially adjusting the barcode scanning settings.  This may improve the reliability of barcode detection, but might not fully resolve the issue in all cases.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request if you have any suggestions or improvements.