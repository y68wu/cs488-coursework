# CS488 coursework source archive

Private source snapshots for four distinct CS488 computer-graphics assignments found in the local `cs488` folder. Each assignment has its own `src/main.cpp`; the hashes differ, so these are not copies of the same final project.

| Folder | Topic | Main implementation |
| --- | --- | --- |
| [`a0/`](a0/) | Image gradient warm-up | Pixel-color computation |
| [`a1/`](a1/) | Software rasterization | Projection, barycentric fill, depth, texture interpolation |
| [`a2/`](a2/) | Ray tracing | Intersection, shadows, reflection/refraction, environment mapping |
| [`a3/`](a3/) | Particle systems | Integration, collision, constraints, gravitational fields |

The separate [public sand-simulation repository](https://github.com/y68wu/cs488-sand-simulation) contains the final project; its `src/main.cpp` matches the local `final_project` copy. An older `cs488/cs488` folder and the saved remote snapshot match each other but not the final project, so they have not been mislabeled as additional original projects.

This archive contains code and CMake files only. Course-provided framework headers and third-party image helpers are included for context, not claimed as original work. Build directories, duplicate submission/backup folders, compiled programs, third-party GLEW, media assets, and assessment material are excluded. The original local folders remain untouched. A complete build may require the original course framework and media files.
