# 3D Vessel Reconstruction (Frangi + Marching Cubes)

Pipeline:
1) Load NIfTI MRI volume (.nii/.nii.gz) with NiBabel
2) Normalize intensities
3) Crop + downsample ROI
4) Frangi vesselness filtering
5) Percentile threshold + morphology cleanup
6) Marching cubes → 3D mesh
7) Plotly visualization

## Dataset
Cui, Y., Huang, H., & Liu, J. (2023). *Macaque angiography dataset*. OpenNeuro. [Dataset]
https://doi.org/10.18112/openneuro.ds004620.v1.0.0

## Install
pip install -r requirements.txt
