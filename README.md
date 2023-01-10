# USC BA estimator
We provide Python code to estimate brain age (BA) from a raw T1-weighted MRI scan (brain.mgz file). Our architecture takes as input a T1-weighted MRI scan and processes it as described in the original publication cited below. 
Sample code to calculate BA in a sample subject is provided in "/3D-CNN/ONNX_demo.ipynb". Our onnx file, which contains the compressed model architecture, is in the Models folder. We suggest using Google Colab or Jupyter notebook to execute our code. The notebook tries to install the required python packages by escaping into the shell and calling pip. If you are pre-installing them yourself, then no need to run this "!pip ..." command. It is mostly useful when setting up your google colab environment for the first time. 
This software is valid for estimating the brain ages of persons whose chronological age is over 20. For persons under age 21, estimated brain ages may not be accurate.

Direct all questions and comments to irimia.laboratory@gmail.com. Please don't forget to acknowledge the original publication when using this code:

Yin, Chenzhong, et al. "Anatomically interpretable deep learning of brain age captures domain-specific cognitive impairment." Proceedings of the National Academy of Sciences 120.2 (2023): e2214634120.


