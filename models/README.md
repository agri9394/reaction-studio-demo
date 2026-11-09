# Segmentation model provenance

- File: `selfie_segmenter.tflite`
- Google MediaPipe SelfieSegmenter, square 256×256, float16, version 1.
- Download: https://storage.googleapis.com/mediapipe-models/image_segmenter/selfie_segmenter/float16/1/selfie_segmenter.tflite
- Documentation: https://developers.google.com/edge/mediapipe/solutions/vision/image_segmenter
- SHA-256: `191ac9529ae506ee0beefa6b2c945a172dab9d07d1e802a290a4e4038226658b`

The runtime comes from the lockfile-pinned `@mediapipe/tasks-vision` npm package
(Apache-2.0); `scripts/prepare-vision-assets.mjs` copies its WASM assets during
build/dev setup. The app serves the runtime and model itself. Enabling the effect
does not send camera frames to Google or any other service.
