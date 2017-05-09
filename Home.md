# Ideas summary


| Tech    | target                  | features                    | GT                              | Misc                               |
|:-------:|:-----------------------:|:---------------------------:|:-------------------------------:|:----------------------------------:|
| deep    |  slide (Cap vs Healthy) | (T2w,ADC,Ktrans) as (R,G,B) | Slide                           | Image net transfer learning        |
|         |                         |                             |                                 |                                    |
|         |  volume (cap vs h)      | registered Prostate volume  | Patient (need healty pattients) |                                    |
|         |                         | Fit a concatenation of      |                                 |                                    |
|         |                         | T2, ADC, Ktrans             |                                 |                                    |
|         |                         |                             |                                 |                                    |
|         | texton                  | XxX voxel across Modalities | Voxel                           | Enough data (10k x patient)        |
|         |                         | and time                    |                                 |                                    |
|         |                         |                             |                                 |                                    |
|         | F-CNN                   | (T2w,ADC,Ktrans) as (R,G,B) | Voxel                           |                                    |
|         |                         |                             |                                 |                                    |
|         | F-CNN                   | registered like in 2        | Voxel                           |  (ideal DL) but we don't have data |
|         |                         |                             |                                 |                                    |
|         | Real transfer learning  |                             |                                 |   RESEARCH                         |
|         |                         |                             |                                 |                                    |
| Common  |                         |                             |  Voxel                          |  reuse PhD                         |
|         |                         |                             |                                 |                                    |
|         |                         |                             |  voxel                          |   Use superpixels                  |
|         |                         |                             |                                 |                                    |


### Type of GT


## Support material
[Guillaume's PhD](https://github.com/glemaitre/phd_thesis/blob/master/thesis.pdf) and [Geert Litjens' PhD](ProstatePhD2.pdf)
