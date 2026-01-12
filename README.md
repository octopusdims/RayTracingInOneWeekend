# My Ray Tracing Journey

This repository tracks my progress through the [Ray Tracing in One Weekend](https://raytracing.github.io/) book series. My goal is to build a physically-based renderer from the ground up while mastering C++ and the fundamentals of computer graphics.

## 📌 Project Roadmap

I am currently working through the series in three stages. Each stage aims to implement more complex light-matter interactions and performance optimizations.

### 🏁 Phase 1: In One Weekend

*Status: 🛠 In Progress*

* [x] Implement basic `vec3` and `ray` classes
* [ ] Create a simple sphere renderer
* [ ] Implement surface normals and multiple objects
* [ ] **Antialiasing** (Multi-sampling)
* [ ] **Materials**:
* [ ] Diffuse (Lambertian)
* [ ] Metal (Reflection)
* [ ] Dielectrics (Refraction/Glass)


* [ ] Camera with **Defocus Blur** (Depth of Field)
* [ ] Render the Final Scene

### 🌲 Phase 2: The Next Week

*Status: ⏳ Planned*

* [ ] Bounding Volume Hierarchies (BVH)
* [ ] Texture Mapping (Solid & Image textures)
* [ ] Perlin Noise
* [ ] Quadrilaterals & Lights
* [ ] Volumes (Fog and Smoke)

### 🌓 Phase 3: The Rest of Your Life

*Status: ⏳ Planned*

* [ ] Importance Sampling
* [ ] Generating Random Directions
* [ ] Orthonormal Bases

---

## 📂 Directory Structure

I've organized the project to allow shared utilities across all three books:

```text
.
├── src/
│   ├── common/        # Shared header-only utilities (vec3, ray, camera, etc.)
│   ├── weekend/       # Book 1: Ray Tracing in One Weekend
│   ├── next_week/     # Book 2: Ray Tracing: The Next Week (BVH, Textures, Volumes)
│   └── rest_of_life/  # Book 3: Ray Tracing: The Rest of Your Life (Importance Sampling)
├── output/            # Rendered images (.ppm or .png)
├── CMakeLists.txt     # Build configuration
└── README.md

```

## 🛠 Build & Run

1. **Configure:** `cmake -B build`
2. **Build:** `cmake --build build --config Release`
3. **Execute:** `./build/weekend > output/result.ppm`

---

## 📓 Learning Notes
**Comming soon.**
