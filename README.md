## Deep Weighted Averaging Classifiers

This code is to accompany the paper *Deep Weighted Averaging Classifiers*, by Dallas Card, Michael Zhang, and Noah S. Smith, to appear at FAT* 2019.

It enables running the DWAC models and the comparable softmax models discussed in the paper. The four relevant directories for this are `cifar`, `mnist`, `tabular`, and `text`, the latter two of which provide support for multiple datasets.

To run any of these, from the main directory, use, for example::

`python -m text.run --model [basline|dwac] --dataset [dataset] --device [GPU number]`

Most of the required datasets will be downloaded and preprocessed automatically.

Please use `-h` to see additional options.


### Requirements

- python3
- pytorch 0.4
- torchvision
- numpy
- scipy
- pandas
- spacy
- scikit-learn

### References

If you find this code or paper useful, please include a citation to:


* Dallas Card, Michael Zhang, and Noah A. Smith. Deep Weighted Averaging Classifiers. In *Proceedings of FAT\** (2019).
