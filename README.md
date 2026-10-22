# ScanOnce_LocalizeAnywhere_ICVGIP26
Repository hosting supplementary and paper related files of the ICVGIP26 submission

# Scan Once, Localize Anywhere: Real-Time Monocular Localization in Gaussian Splatting Maps on Edge Devices

**Vishnu R Rao**<sup>1</sup>, **Bharadwaj Amrutur**<sup>2,1</sup>

<sup>1</sup>ARTPARK, Bangalore, India · <sup>2</sup>Indian Institute of Science, Bangalore, India

*17th Indian Conference on Computer Vision, Graphics and Image Processing (ICVGIP 2026), Kolkata, India*

---

## Supplementary material

**[Supplementary.pdf](Supplementary.pdf)**

The supplementary material accompanies the main paper and contains:

- **S1 — Complete stability-filter grid.** Landmarks retained and 5 cm / 5° success rate for all 70 configurations: seven 7-Scenes scenes × two splat representations (2DGS-regularized, photometric 3DGS) × five filter settings.
- **S2 — Surveyed-grid frame recovery.** Per-marker fit residuals of the rigid splat-to-world transform recovered from the 14 surveyed markers.
- **S3 — Surveyed-grid held-out evaluation.** Two-fold and leave-one-out results, in which every scored marker is held out of the transform fit that scores it.
- **S4 — Synthetic motion blur.** Localization on 7-Scenes and the warehouse grid under controlled linear motion blur of increasing length.

## Citation

```bibtex
@inproceedings{rao2026scanonce,
  title     = {Scan Once, Localize Anywhere: Real-Time Monocular Localization
               in Gaussian Splatting Maps on Edge Devices},
  author    = {Rao, Vishnu R and Amrutur, Bharadwaj},
  booktitle = {Proceedings of the 17th Indian Conference on Computer Vision,
               Graphics and Image Processing (ICVGIP)},
  year      = {2026}
}
```

## Note
The accompanying video shows real-time operation with a handheld camera in our experimental space. This demonstration is purely qualitative and was not evaluated against ground truth. The video was generated from a RealSense D455 rosbag, replayed through the desktop configuration described in the paper. Although the D455 outputs multiple camera streams and IMU data, we recorded only the RGB stream, demonstrating complete monocular localization with no per-scene training and no rendering at query time.

## Contact

Vishnu R Rao — Raise an issue
