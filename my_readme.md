## 1
```
conda install ninja pybind11 cmake boost

pip install kaolin==0.17.0 -f https://nvidia-kaolin.s3.us-east-2.amazonaws.com/torch-2.5.1_cu124.html

pip install "git+https://github.com/facebookresearch/pytorch3d.git@stable"

pip install "git+https://github.com/NVlabs/nvdiffrast.git"
```

## 2
```
cd mycpp
cmake -B build -S . 
cmake --build ./build --config Release --target ALL_BUILD
```
mycpp\build\Release\mycpp.cp310-win_amd64.pyd 到 mycpp\build\

## 3
```
cd bundlesdf/mycuda
python -m pip install -e .
```

## 4
```
pip install trimesh joblib imageio psutil pandas open3d opencv-python matplotlib transformations ruamel.yaml kornia omegaconf h5py scikit-learn
```

```
python run_demo.py
```