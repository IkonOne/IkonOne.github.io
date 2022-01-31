---
name: RTLib - A Raytracing Library
type: Coursework
goal: Implement a reference ray-tracer and explore methods of optimization.
tags: C++ CMake Ray-Tracing 3D_Graphics Data_Structures
image: rtlib.png
order: 01
---

- Implemented my 4th raytracer as part of course requirements
- Went above and beyond, implementing an [emberrassingly parallel bounding volume hierarchy construction algorithm](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=-50qJW8AAAAJ&citation_for_view=-50qJW8AAAAJ:9yKSN-GCB0IC) that executes in O(lgn) time given perfect parallelism
- The result was a raytracer that could render 20,000 spheres and 2,000 triangles at a depth of 7 in under a minute on the CPU