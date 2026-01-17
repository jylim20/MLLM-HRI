# MLLM-HRI

MLLM Engagement Prediction in Uncontrolled and Controlled HRI | [Paper]() | [Bibtex](#citation) |
(Released on March, 2026)

## Data Preprocessing
Samples are stratified into training, validation, and test sets (5:2:3). To mitigate bias and ensure equitable evaluation, samples from users assigned to the test sets were excluded from model training. The validation and test folds were constructed to preserve the original data distribution. The specific splits for both datasets (UE-HRI and eHRI) can be found here.

### UE-HRI
The dataset exhibited a significant imbalance between $EG$ and $SED$ instances, at a ratio of 9:1. To address this issue, we first incorporated all available $SED$ samples and then randomly sampled $EG$ events to align with the dataset's true distribution. The training set was sampled to a balanced 5:5 ratio, while the test and validation sets preserved the imbalanced distribution.

### eHRI
The engagement scores in this dataset are approximately normal distributed. Then, random sampling is implemented across train/validation/test sets according to the original distribution.

## Citation
If you find this work useful for your research, please cite
```bibtex

```

## Feedback
Suggestions and opinions on this work (both positive and negative) are greatly welcomed.

## License and Copyright
The project is open source under MIT license (see the ``` LICENSE ``` file). 
