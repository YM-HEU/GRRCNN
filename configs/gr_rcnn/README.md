## Global Recurrent Mask R-CNN (GR R-CNN)

  This repository implements the Global Recurrent Mask R-CNN (GR R-CNN), an end-to-end algorithm aimed at improving multi-scale segmentation of ship instances in marine environments.
Key Features:

### Recurrent Enhanced Feature Pyramid Network (RE-FPN):

  A novel module that uses a feature recurrence and bidirectional chaining fusion mechanism to deeply integrate both deep and shallow features. This enables effective extraction of multi-scale features and semantic information from images.

### Fine-Grained Global Fusion Mask Head (FGFMH):

  This module utilizes a fine-grained multi-layer receptive field extraction mechanism to improve the capture of global and multi-scale features. In combination with RE-FPN, it effectively enhances the overall performance of ship instance segmentation.

### Performance:

  Experiments on the MS COCO test-dev, PASCAL VOC, and custom OVSD datasets show accuracy improvements of 1.8%, 3.29%, and 1.3%, respectively. Our approach outperforms several state-of-the-art methods and offers valuable insights for advancing research on multi-scale instance segmentation of ships in complex environments.

### Instance segmentation results on the COCO val

|    Backbone     |  Style   |   AP  | AP{50} | AP{75} | AP{S} | AP{M} | AP{L  |

|    R-101-FPN    |  pytorch | 37.13 |  58.29 | 39.96  | 17.41 | 40.17 | 54.30 |

### Instance segmentation results on the Pascal VOC2012

|    Backbone     |  Style   |   AP  | AP{50} | AP{75} | AP{S} | AP{M} | AP{L}  |                                                                                                                                                                                                                                                                                                                                                             

|    R-101-FPN    |  pytorch | 31.51 |  56.36 | 30.74  | 9.25  | 17.26 | 38.15  |

### Instance segmentation results on the OVSD

|    Backbone     |  Style   |   AP  | AP{50} | AP{75} | AP{S} | AP{M} | AP{L}  |
|    R-101-FPN    |  pytorch | 32.86 |  55.49 | 34.21  | 12.93 | 33.82 | 48.15  |

