Code for the paper: "Hyperspectral Image Super-resolution via Deep Spatio-spectral Attention Convolutional Neural Networks"

### plateform.
The proposed network is trained on Python 3.7.4 with Tensorflow 1.14.0 + cuda10.0 + cudnn 7.6.5

### demo.
HSRnet.py: The training and testing code
models(cave): The model trained with CAVE data
models(harvard): The model trained with Harvard data

### two test datasets.
test_cave_demo.mat : One testing image from CAVE dataset 
(download link: https://www.dropbox.com/s/u1cr6lye6xqppv0/test_cave_demo.mat?dl=0)

test_harvard_demo.mat : One testing image from Harvard dataset 
(download link: https://www.dropbox.com/s/5a3s7cijqfkwx13/test_harvard_demo.mat?dl=0)


### bib refer.
If you find this code helpful, please kindly cite:

BibTeX:
    @article{Hu2021Hyperspectral,
      title={Hyperspectral Image Super-resolution via Deep Spatio-spectral Attention Convolutional Neural Networks},
      author={ Hu, Jin-Fan and Huang, Ting-Zhu and Deng, Liang-Jian and Jiang, Tai-Xiang and Vivone, Gemine and Chanussot, Jocelyn},
      journal={IEEE Transactions on Neural Networks and Learning Systems},
      year={2021},
      publisher={IEEE}
    }
