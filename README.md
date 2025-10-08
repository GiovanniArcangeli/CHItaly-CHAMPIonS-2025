# CHItaly-CHAMPIonS-2025
Presentation for CHItaly 2025 - CHAMPIonS workshop: an intelligent three-stage system for soccer ball tracking and field detection, combining temporal validation, realistic interpolation, and CNN-based line recognition.

This repository contains the 20-minute presentation for the CHItaly 2025 workshop, based on the paper “Intelligent Ball Tracking System for Soccer: A Spatiotemporal Approach with Field Line Recognition.”

The work introduces a three-stage pipeline for accurate and robust ball tracking in soccer videos:
1.Candidate harvesting using YOLOv8 to maximize recall.
2.Temporal look-ahead validation to remove false positives and ensure consistency.
3.Physically realistic interpolation to handle short occlusions.

The system is integrated with an hybrid field detection module combining CNN-based segmentation and geometric line refinement (Hough transform + clustering).
Together, these components enable automatic in/out-of-play detection from broadcast match footage.

The presentation slides summarize the motivation, methodology, results, and future work of this project.

For the presentation: https://github.com/GiovanniArcangeli/CHItaly-CHAMPIonS-2025/releases/download/sports-analytics/CHItaly2025-Arcangeli.pptx
