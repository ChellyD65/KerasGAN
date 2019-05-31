# KerasGAN
A GAN implemented in Keras.  This is essentially a fork of https://github.com/eriklindernoren/Keras-GAN/tree/master/wgan_gp with some tweaks (e.g. flexible image sizes, etc).

## Tested in this environment
gcc/6.2.0

conda2/4.2.13

cuda/9.0

### Conda environment info:

channels:
  - anaconda
  - conda-forge
  - bioconda
  - defaults
dependencies:
  - _tflow_select=2.1.0=gpu
  - absl-py=0.7.1=py36_0
  - anaconda=custom=py36hbbc8b67_0
  - astor=0.7.1=py36_0
  - blas=1.0=mkl
  - c-ares=1.15.0=h7b6447c_1
  - ca-certificates=2019.1.23=0
  - certifi=2019.3.9=py36_0
  - cudatoolkit=10.0.130=0
  - cudnn=7.3.1=cuda10.0_0
  - cupti=10.0.130=0
  - freetype=2.9.1=h8a8886c_1
  - gast=0.2.2=py36_0
  - grpcio=1.16.1=py36hf8bcb03_1
  - h5py=2.9.0=py36h7918eee_0
  - hdf5=1.10.4=hb1b8bf9_0
  - intel-openmp=2019.3=199
  - jpeg=9b=habf39ab_1
  - keras-applications=1.0.7=py_0
  - keras-base=2.2.4=py36_0
  - keras-gpu=2.2.4=0
  - keras-preprocessing=1.0.9=py_0
  - libffi=3.2.1=he1b5a44_1006
  - libgcc-ng=8.2.0=hdf63c60_1
  - libgfortran-ng=7.3.0=hdf63c60_0
  - libpng=1.6.37=hbc83047_0
  - libprotobuf=3.6.1=hd408876_0
  - libstdcxx-ng=8.2.0=hdf63c60_1
  - libtiff=4.0.10=h2733197_2
  - markdown=3.1=py36_0
  - mkl=2019.3=199
  - mkl_fft=1.0.10=py36ha843d7b_0
  - mkl_random=1.0.2=py36hd81dba3_0
  - mock=2.0.0=py36_0
  - ncurses=6.1=hf484d3e_1002
  - numpy=1.16.3=py36h7e9f1db_0
  - numpy-base=1.16.3=py36hde5b4d6_0
  - olefile=0.46=py36_0
  - openssl=1.1.1=h7b6447c_0
  - pbr=5.1.3=py_0
  - pillow=6.0.0=py36h34e0f95_0
  - pip=19.1=py36_0
  - protobuf=3.6.1=py36he6710b0_0
  - python=3.6.7=h381d211_1004
  - pyyaml=5.1=py36h7b6447c_0
  - readline=7.0=hf8c457e_1001
  - scipy=1.2.1=py36h7c811a0_0
  - setuptools=41.0.1=py36_0
  - six=1.12.0=py36_0
  - sqlite=3.26.0=h67949de_1001
  - tensorboard=1.13.1=py36hf484d3e_0
  - tensorflow=1.13.1=gpu_py36h3991807_0
  - tensorflow-base=1.13.1=gpu_py36h8d69cac_0
  - tensorflow-estimator=1.13.0=py_0
  - tensorflow-gpu=1.13.1=h0d30ee6_0
  - termcolor=1.1.0=py36_1
  - tk=8.6.9=h84994c4_1001
  - werkzeug=0.15.2=py_0
  - wheel=0.33.1=py36_0
  - xz=5.2.4=h14c3975_1001
  - yaml=0.1.7=h96e3832_1
  - zlib=1.2.11=h14c3975_1004
  - zstd=1.3.7=h0b5b093_0
