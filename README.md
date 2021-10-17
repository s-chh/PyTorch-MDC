# PyTorch-MDC
Unofficial PyTorch implementation of Maximum Domain Confusion loss from [Simultaneous Deep Transfer Across Domains and Tasks](https://arxiv.org/abs/1510.02192) for Unsupervised Domain Adaptation.


<br>
<br>
Results:
<br>

 | Dataset    |Source Only    | MDC |
--- | --- | --- | 
SVHN &#10230; MNIST | 61.2|80.2 |
MNIST &#10230; USPS | 81.8 | 96.2|
USPS &#10230; MNIST | 49.4| 97.5|
SyDigits &#10230; SVHN | 87.9| 91.5|
SySigns &#10230; GTSRB | 91.0| 93.3|
