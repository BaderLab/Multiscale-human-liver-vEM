## Note

`predict_on_EM_slices.ipynb` is a step-by-step demo, specific to this
repository, showing SAM2 mask propagation applied to example human liver
volume EM slices (see the main [README](../../README.md)).

The remaining notebooks (`automatic_mask_generator_example.ipynb`,
`image_predictor_example.ipynb`, `video_predictor_example.ipynb`) and their
image/video assets are unmodified examples from the upstream
[SAM2](https://github.com/facebookresearch/sam2) repository (Apache License
2.0, see `../LICENSE`). They demonstrate general SAM2 usage on stock
images/video and are not specific to the liver volume EM pipeline — for the
EM-specific, scriptable equivalent, see `sam2maskpropagator.py` at the
repository root.
