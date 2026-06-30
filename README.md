# Tecolotl Ranch

## Overview

In ranches, stables, and open ecosystems, animal supervision still depends heavily on manual patrols, direct observation, or later image review. This limits the ability to understand in real time what is happening in the field: how many cattle are in a specific area, whether an animal is out of place, or whether wildlife such as deer, wild boars, or coyotes is present. In large outdoor spaces with vegetation, shadows, fences, corrals, and changing weather conditions, this supervision can become slow, inconsistent, and difficult to scale.

**Teco Lab Ranch** is the livestock and ranch monitoring vertical of Teco Lab. It was created to explore how artificial intelligence, computer vision, and drone-based monitoring can support rural and environmental supervision. The initial goal of this vertical is to analyze aerial images and help with two main tasks: **counting cattle** and **detecting wildlife**, especially deer, wild boars, and coyotes.

Inspired by tools such as MegaDetector, Teco Lab Ranch does not assume that every model must be built from scratch. Before training a custom model, the project will evaluate pretrained models such as MegaDetector, COCO-based models, and ImageNet-based models on our first labeled batches. This will help us identify which model performs best as an initial baseline, whether it can be adapted through transfer learning, or whether a specialized model is needed for our environment.

Unlike a generic camera trap solution, Teco Lab Ranch focuses on aerial images and rural scenarios. This includes stables, corrals, ranch areas, and open ecosystems where drone altitude, camera angle, weather, shadows, fences, and partial occlusions can affect model performance. For this reason, the project also considers metadata such as flight altitude, weather conditions, and environment type to better understand when the system works well and when it needs improvement.

The goal is not to fully replace human supervision, but to reduce manual review time and help identify the scenes that matter. In its first stage, Teco Lab Ranch will focus on animal detection and cattle counting in controlled environments, such as stables or corrals, where animals are limited in space and drone images can be captured more consistently. Later, the system may be extended to wildlife detection in the Coahuila ecosystem.

## What Teco Lab Ranch does

Teco Lab Ranch aims to:

- Analyze live aerial images captured from drones.
- Detect the presence of animals in rural environments.
- Count and move cattle in controlled spaces.
- Prepare a foundation for future wildlife detection models focused on deer, wild boars, and coyotes.

## Why this matters

The value of Teco Lab Ranch is to turn difficult-to-review visual data into useful information for decision-making. For ranching, this can support faster cattle counting, animal location, and field supervision. For environmental monitoring, it can help detect wildlife presence and reduce the amount of manual review needed.

The project combines drones, computer vision, and field data to build a tool adapted to rural monitoring in northern Mexico.



## 1 min pitch

**Teco Lab Ranch** is an artificial vision initiative designed to transform the way ranches understand and monitor their land.

By combining drones, artificial intelligence, and computer vision, Teco Lab Ranch seeks to give ranchers a smarter view of what is happening in the field: where animals are located, how livestock moves, and when wildlife appears in the environment.

In large rural areas, supervision is still limited by distance, terrain, weather, visibility, and human availability. We turns aerial imagery into intelligent field insight, helping reduce manual observation and enabling faster, more informed decisions.

The vision is to build an AI-powered monitoring system adapted to real ranching conditions in northern Mexico, where cattle, wildlife, vegetation, shadows, fences, and open terrain create a complex environment that traditional supervision cannot easily scale.
