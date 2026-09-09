# Data Card

## Dataset

- Name: First-Person Perspective Driving Video Collection
- Product ID: `VID-20260728-151612-899`
- Provider: Thordata DataMall
- Viewpoint: Driver-seat / first-person view
- Modality: Video
- Public preview: [Hugging Face dataset](https://huggingface.co/datasets/thordata/first-person-driving-video-v1)
- Product page: [Thordata DataMall](https://datamall.thordata.com/datasets/VID-20260728-151612-899)

## Overview

This public preview contains a first-person driving video showing scenes such as roadside stops, open mountain roads, valley roads, curving roads, and vehicles ahead.

The public preview is not the complete commercial dataset.

## Repository Scope

This GitHub repository provides documentation and metadata for the public preview. The source video file is hosted on Hugging Face.

This repository does not contain the complete commercial dataset and does not include unrelated video products.

## Annotations

The public preview includes coarse scene-segment annotations.

The annotations describe visible scene context and driving events. They are not lane-level, object-level, or frame-accurate autonomous-driving annotations.

Any derived frame metadata should be treated as reviewable metadata unless a separate annotation review confirms its accuracy.

## Intended Use

The preview may support:

- First-person video understanding
- Computer vision research
- Driving scene understanding
- Autonomous-driving research
- Multimodal AI and vision-language model prototyping
- Video retrieval workflows
- Dataset structure and metadata evaluation

Use remains subject to the applicable sample usage terms.

## Known Limitations

- The public preview represents only a limited sample.
- It does not represent the full commercial dataset.
- Scene annotations are coarse and may require further review.
- The preview should not be treated as a complete autonomous-driving benchmark.
- This data card does not grant additional rights beyond the applicable sample terms.

## Privacy And Rights Review

Before using or redistributing the preview, review the content for:

- Faces
- Voices
- License plates
- GPS or precise location information
- Addresses
- Commercial signs
- Private locations
- Other personal or sensitive information

Content that cannot be publicly released under the applicable terms should be removed, redacted, or excluded.

## Access

- [Hugging Face public preview](https://huggingface.co/datasets/thordata/first-person-driving-video-v1)
- [DataMall commercial product](https://datamall.thordata.com/datasets/VID-20260728-151612-899)

For commercial access or licensing questions, contact the [Thordata team](https://www.thordata.com/contact-us).

## Version

- Data card version: `0.1.0`
- Product ID: `VID-20260728-151612-899`
- Review status: Public preview documentation
