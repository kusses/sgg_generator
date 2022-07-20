# Scene graph generation interface
scene graph generator based on scene graph benchmark project

This code is based on [scene graph benchmark](https://github.com/microsoft/scene_graph_benchmark.git)

Before applying this code, there are 3 things should be prepared.

## Pretrained models
- **vinvl_vg_x152c4.pth -> object and its attribute detection**
- **model_final.pth -> RelDn scene graph generation model**

## Configuration files
- **vinvl_x152c4.yaml**
- **rel_danfeiX_FPN50_reldn.yaml**


## Frequently used predicated 
- **label_danfeiX_clipped.freq_prior.npy**
