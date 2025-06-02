# 🧊 Framer 3D Assets Repository

This repository hosts 3D `.glb` files used in my Framer portfolio and interactive design projects.

## 🔗 Live File Access (via GitHub Pages)

GitHub Pages is enabled on this repo, so all files can be accessed publicly like this:


### ✨ Examples

- `abstract_gold_ring.glb`  
  👉 https://yourusername.github.io/framer-3d-assets/abstract_gold_ring.glb

- `floating_card.glb`  
  👉 https://yourusername.github.io/framer-3d-assets/floating_card.glb

---

## 🧩 How to Use in Framer

To embed a 3D model in Framer using `<model-viewer>`, use this code:

```html
<iframe srcdoc="
  <script type='module' src='https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js'></script>
  <model-viewer 
    src='https://yourusername.github.io/framer-3d-assets/your-model.glb' 
    alt='3D Model' 
    auto-rotate 
    camera-controls 
    style='width: 100%; height: 100%;'>
  </model-viewer>
" width="100%" height="400px" style="border: none;"></iframe>
