<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png" /></a> This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

# Real Acoustic Fields: An Audio-Visual Room Acoustics Dataset and Benchmark
<p align="left" style="font-size:20px; font-weight:600;">CVPR 2024</p>

We present the Real Acoustic Fields (RAF) dataset that captures real acoustic room data from multiple modalities. The dataset includes high-quality and densely captured room impulse response data paired with multi-view images, and precise 6DoF pose tracking data for sound emitters and listeners in the rooms.

<div align = "center"><img src="media/RAF.jpg" style="border-radius: 15px;" /></div>
<p align="center" style="margin: 2em auto;">
    <a href='https://facebookresearch.github.io/real-acoustic-fields/' style='padding-left: 0.5rem;'><img src='https://img.shields.io/badge/Real--Acoustic--Fields-Project_page-orange?style=flat&logo=github&logoColor=orange' alt='Project Page'></a>
    <a href=''><img src='https://img.shields.io/badge/arXiv-Paper_PDF-red?style=flat&logo=arXiv&logoColor=green' alt='Paper PDF'></a>
  </p>

## Dataset
The [Real Acoustic Fields dataset]() is hosted on AWS S3.
We recommend using the AWS command line interface (AWS CLI), see [AWS CLI installation instructions](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html).


## Citation
If you find this repository and dataset useful in your research, please consider giving a star ⭐ and cite our CVPR 2024 paper by using the following BibTeX entrys.
```
@inproceedings{chen2024RAF,
      author    = { Chen, Ziyang and 
                    Gebru, Israel D. and 
                    Richardt, Christian and 
                    Kumar, Anurag and
                    Laney, William and
                    Owens, Andrew and 
                    Richard, Alexander},
      title     = {Real Acoustic Fields: An Audio-Visual Room Acoustics Dataset and Benchmark},
      journal   = {The IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR)},
      year      = {2024},
    }
```

## License
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>, as found in the LICENSE file.