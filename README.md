
<div align="center">
<h2>Rooftop Detection from Historical Aerial Imagery Using Deep Learning in Downtown Charleston, SC</h2>
<a href='https://pengyu-gis.github.io/' target='_blank'>Pengyu Chen</a>, 302, Cuizhen Wang, Sicheng Wang<br>
Department of Geography, University of South Carolina
</div>

### Abstract
>Rooftop detection is essential for urban analysis, infrastructure monitoring, and disaster assessment. However, applying detection techniques to historical aerial imagery is challenged by low resolution and high noise levels. This study introduces a workflow tailored for historical datasets, integrating image colorization with DeOldify, GeoJSON ground truth data, and advanced object detection models. We evaluated three methods: (1) fine-tuning a Mask R-CNN model with a ResNet-50 backbone, (2) BoxPrompt-based detection using SAM2, and (3) TextPrompt-learning with SAM2. Our results demonstrate that colorization significantly enhances historical imagery quality, improving detection performance. The BoxPrompt-based approach achieved an Intersection over Union (IoU) exceeding 90\%, offering high accuracy but requiring manual input, which affects reproducibility. In contrast, the fully automated TextPrompt-learning method attained over 80\% IoU, providing automation at the expense of controllability due to prompt variability. The fine-tuned Mask R-CNN model strikes a balance between automation and controllability, achieving an average precision of 72\% and outperforming zero-shot methods. Additionally, models trained on colorized images achieved higher average precision (72\%) compared to those trained on grayscale imagery (44\%). This workflow provides valuable tools and insights for historical GIS applications, urban analysis, and remote sensing studies.

### Overall framework diagram:
<div align="center">

<img src="https://github.com/user-attachments/assets/78f32e1f-5fe6-41d1-9cb8-810f9ee20a0b" alt="Workflow" width="75%">

</div>
