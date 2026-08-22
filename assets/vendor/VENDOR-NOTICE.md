# Vendored runtime dependencies

These files are served from the same origin as the portfolio so the core page does not depend on a public CDN at runtime.

- Three.js `0.180.0`: `three/three.module.js`, its matching `three.core.js`, `GLTFLoader`, `DRACOLoader`, `BufferGeometryUtils`, and the matching Draco decoder files. Three.js is MIT licensed; see `three/LICENSE`.
- GSAP `3.15.0`: `gsap/gsap.min.js` and `gsap/ScrollTrigger.min.js`. Version and copyright notices are preserved in the distributed files.

When updating either library, update the core file, add-ons/decoder files, and `index.html` paths as one tested compatibility set.
