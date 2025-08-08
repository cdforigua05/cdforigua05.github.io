---
title: "Egocast: Forecasting egocentric human pose in the wild"
collection: publications
category: conferences
permalink: /publication/Egocast
excerpt: A bimodal Transformer that forecasts future 3D body poses from first-person video and headset motion using pseudo-ground-truth estimation.
date: 2025-02-17
venue: 'WACV 2025'
paperurl: 'https://arxiv.org/pdf/2412.02903'
bibtexurl: 
citation: 'Escobar, M., Puentes, J., <strong>Forigua, C.</strong>, Pont-Tuset, J., Maninis, K. K., & Arbelaez, P. (2025, February). Egocast: Forecasting egocentric human pose in the wild. In 2025 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) (pp. 5831-5841). IEEE.'
---

Abstract
======
Accurately estimating and forecasting human body pose is important for enhancing the user's sense of immersion in Augmented Reality. Addressing this need, our paper introduces EgoCast, a bimodal method for 3D human pose forecasting using egocentric videos and proprioceptive data. We study the task of human pose forecasting in a realistic setting, extending the boundaries of temporal forecasting in dynamic scenes and building on the current framework for current pose estimation in the wild. We introduce a current-frame estimation module that generates pseudo-groundtruth poses for inference, eliminating the need for past groundtruth poses typically required by current methods during forecasting. Our experimental results on the recent Ego-Exo4D and Aria Digital Twin datasets validate EgoCast for real-life motion estimation. On the Ego-Exo4D Body Pose 2024 Challenge, our method significantly outperforms the state-of-the-art approaches, laying the groundwork for future research in human pose estimation and forecasting in unscripted activities with egocentric inputs.