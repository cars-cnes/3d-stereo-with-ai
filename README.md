# 3d-stereo-with-ai

This workshop will present CARS 3D framework and explain how to use it from command line and python API to generate Digital Surface Models from stereo images.
Particularly, the presentation will detail AI improvement in stereo matching step to improve DSM accuracy.

From glaciology, smart cities to business intelligence studies, more and more scientific and business applications needs 3D earth elevation information named Digital Surface Models.

In the same time, a lot of High and Very High resolution optical satellite stereo images are available from satellites such as Pléiades, Pléiades Néo, WorldView3.

In this context, automatic, robust and scalable software are needed to generate 3D Digital Surface Models (DSM).

In the frame of future dedicated CO3D constellation, CNES have developed open source CARS tool as a a whole modern 3D Framework intended for massive DSM production with a robust and performant design but also for research aims.
CARS allows therefore to design its own 3D pipeline easily from 3D classical steps.

During this tutorial, we will first present quickly CARS context, objectives and details all its components.

Then, some detailed practical examples will be done:
- Using CARS CLI to generate DSM from large data images using DASK to ensure high scalability.
- Using CARS framework to follow a step by step approach with intermediate results analysis (disparity maps, point clouds, ...).
- Using CARS framework and stereo matching Pandora tool with AI improvement for better DSM accuracy.
