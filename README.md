## Introduction

This dataset contains [CoarseData](https://drive.google.com/open?id=0B0A9UsiwtVTHY0p4em5qUzRISW8) and [FineData](https://drive.google.com/open?id=1z12Ukg-iIF4qM3z6RXKUzYYpl43seO2J) augmented from 3131 images of [300-W](https://ibug.doc.ic.ac.uk/resources/300-W/) with the method described in the paper [3DFaceNet: Real-time Dense Face Reconstruction via Synthesizing Photo-realistic Face Images](https://arxiv.org/abs/1708.00980). CoarseData is constructed by varying poses and expressions of the original images. FineData is constructed by transferring details from other images to the original images. We augment each image 30 times for both CoarseData and FineData.

We also put the augmented dataset and the reconstruction results by our method on [BaiduYun](https://pan.baidu.com/s/1jNVQLXBLbbZSrc8l5zXRIA) with password: vev7.

## Dependencies

To use the CoarseData, one needs the [Basel Face Model](http://faces.cs.unibas.ch/bfm/?nav=1-0&id=basel_face_model), which is used as the parametric identity face model in our method.

## Usage

As introduced in the above, each face image is augmented 30 times in the CoarseData and FineData dataset. With the given information, we can also easily get other useful informations like the corresponding 3D landmark positions and head poses. 

If you have comments or questions, please contact Yudong Guo (gyd2011@mail.ustc.edu.cn) and Juyong Zhang (juyong@ustc.edu.cn).

## License

Please note that this dataset could be used for research purpose only, and any commercial use of the data is prohibited.

## Citation

Please cite the following paper if this dataset helps your research:

	@article{Guo20183DFace,
  		author = {Yudong Guo and Juyong Zhang and Jianfei Cai and Boyi Jiang and Jianmin Zheng},
  		title = {CNN-based Real-time Dense Face Reconstruction with Inverse-rendered Photo-realistic Face Images},
  		journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
  		year = {2018}
	}