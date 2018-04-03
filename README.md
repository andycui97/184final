# CS184 Final Project

### GPU path tracer using NVIDIA OptiX

Our project will aim to implement a raytracer but backed by GPU power using NVIDIA OptiX. We plan to implement all the same features found in project 3-1 and 3-2 such as BVH, importance sampling, adaptive sampling, mirror glass and microfacet materials, and depth of field. Time permitting we will extend our raytracer to include difficult materials such as cloth.  

Andrew Cui, 26032185<br/>
Chris Mitchell, 26251801<br/>
Raymond Ng, 25605575<br/>

### Problem Description

Recent advances in GPU power have made a lot of applications of computer science faster. One of these is ray tracing and rendering in general. After impatiently waiting for project 3 images to render, we ask ourselves: how do we make this faster? We plan to port the whole project including the backend to use OptiX, which requires a deeper understanding of raytracing than required to complete the project. 

### Goals and Deliverables
##### Plan to Deliver
The images from Project 3-1 Part 3 along with Project 3-2 Parts 1, 2, & 4. <br>
Timing data showing time to render scenes with and without GPU as the mesh complexity scales. 
##### Hope to Deliver
Timing showing GPU speedup with various effects and BSDF's. An image with a realistic cloth BSDF also sped up by our Optix ray tracer. Potentially even a set of starter code so that future versions of this class can use a GPU path tracer and people won't have to rely on hive machines. 


### Schedule
Week1: Transfer backend to our best ability to OptiX, load dae/sky/CBspheres_lambertian.dae and produce the simplest Cornell box probably as a mesh. 

Week2: Get BVH working, global illumination. We should have all of Project 3-1 by now. 

Week3: Add mirror, glass, and microfacet materials. Implement depth of field. 

Week4: Timing experiments, writeup, cloth material time permitting.   


### Resources

The OptiX SDK comes with a set of examples. Nvidia also has a developer forum which is a good place to look. 



