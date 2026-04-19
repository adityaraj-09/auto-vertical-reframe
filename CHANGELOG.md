# Changelog

All notable changes to this project are documented in this file. The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and the project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2026-04-19

### Added
- Initial release of the Auto Vertical Reframe CLI.
- Scene-aware vertical reframing pipeline built on YOLOv11 segmentation, MediaPipe face/pose, and PySceneDetect.
- Presets: `talking_head`, `sports`, `pets`, `cars`.
- Handcrafted and DeepGaze-MR saliency backends with CPU/CUDA/MPS selection.
- macOS `run_verthor.command` launcher with native dialogs.
- Debug preview export and JSON summary logging.
