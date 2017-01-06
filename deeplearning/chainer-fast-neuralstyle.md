# Get chainer with GPU support

> git clone https://github.com/pfnet/chainer

install nvidia libs:
* CUDA sdk
* cuDNN sdk
* copy cuDNN files to `c:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0\`

install python libs:
* conda install numpy
* conda install six
* conda install pillow
* conda install cython

> cd chainer
> python setup.py	install

# Get chainer-fast-neuralstyle

> git clone https://github.com/yusuketomoto/chainer-fast-neuralstyle

> python generate.py sample_images/tubingen.jpg -m models/seurat.model -o sample_images/output.jpg -g 0