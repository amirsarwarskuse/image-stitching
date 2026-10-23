# Image Stitching & Panorama

Stitches overlapping photos into one image, or a wide panorama, using SIFT features, RANSAC homography estimation and perspective warping (no `cv2.Stitcher`).

| Two-image stitch | Three-image panorama |
|---|---|
| ![Stitched pair](results/stitched_pair.png) | ![Panorama](results/panorama.png) |

## Run it

```bash
pip install -r requirements.txt
```

Put `1.jpg`, `2.jpg`, `3.jpg` (overlapping photos, ordered left to right) in `images/`, then run `image_stitching.ipynb`.
