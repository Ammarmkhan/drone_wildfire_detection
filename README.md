# Drone based Wildfire Detector
In this project, we use drone images to find fledgling wildfires. The intent - find wildfires before they get 'wild'.

### Process
For this project, we obtained images from [ieee-dataport](https://ieee-dataport.org/open-access/flame-dataset-aerial-imagery-pile-burn-detection-using-drones-uavs#files) . We did our own bounding box based data labelling using label studio and trained our model based on ~ 2000 images.

We ended up adapting resnet_v2 for our usecase. The result was a 0.82 mAP for a 0.5 IOU. 

For a comprehensive overview of our building process, please refer to our [Notion working Notes.](https://cream-lead-5e3.notion.site/Drone-Based-WildFire-Detection-fe8b9a83c71943d1807ddc85ddf6e523)

### Credits
This projects was hosted by the [Aggregate Intellect](https://ai.science/) and done under the guidance of [Andre Erler](https://github.com/aerler) & [Yan Nusinovich](https://github.com/ynusinovich).
