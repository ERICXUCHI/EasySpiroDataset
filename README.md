# EasySpiroDataset
This repository contains EasySpiro Dataset.

## Description
EasySpiro Dataset is a dataset for EasySpiro: Assessing Lung Function via Arbitrary Exhalations on Commodity Earphones. It contains pair-wise samples (audio and IMU) from 50 subjects. Due to the IRB, we provide the samples here for your reference. For more details, please refer to the paper.

If you want to use the dataset, please contact us for further information via email: [cxubs@cse.ust.hk](mailto:cxubs@cse.ust.hk).

## Structure
```
EasySpiroDataset/
├── audio/
│   ├── id_1.wav
│   ├── id_2.wav
│   ├── ...
├── imu/
│   ├── id_1.npy
│   ├── id_2.npy
│   ├── ...
├── Ground_Truth.csv
├── Recommend.csv (recommendation values for each subject)
├── effort_level.json (effort level for each subject, 0: highest, and the higher the value, the lower the effort)
```

## Citation
If you use the EasySpiro Dataset, please cite the following paper [coming soon].

## License
The EasySpiro Dataset is released under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

## Contact
If you have any questions, please contact us via email same as above or simply open an issue in this repository.
