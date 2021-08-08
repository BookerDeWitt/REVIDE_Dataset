# Learning to Restore Hazy Video: A New Real-World Dataset and A New Method (CVPR2021)
The first REal-world VIdeo DEhazing dataset (REVIDE) for supervised training of video dehazing networks.

## Abstract
Most of the existing deep learning-based dehazing methods are trained and evaluated on the image dehazing datasets, where the dehazed images are generated by only
exploiting the information from the corresponding hazy ones. On the other hand, video dehazing algorithms, which can acquire more satisfying dehazing results by exploiting the
temporal redundancy from neighborhood hazy frames, receive less attention due to the absence of the video dehazing datasets. Therefore, we propose the first **REal-world VIdeo
DEhazing (REVIDE)** dataset which can be used for the supervised learning of the video dehazing algorithms. By utilizing a well-designed video acquisition system, we can
capture paired real-world hazy and haze-free videos that are perfectly aligned by recording the same scene (with or without haze) twice. Considering the challenge of exploiting temporal redundancy among the hazy frames, we also develop a Confidence Guided and Improved Deformable Network (**CG-IDN**) for video dehazing. The experiments demonstrate that the hazy scenes in the REVIDE dataset are more realistic than the synthetic datasets and the proposed algorithm also performs favorably against state-of-the-art dehazing methods.

## Paper & Dataset
[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Learning_To_Restore_Hazy_Video_A_New_Real-World_Dataset_and_CVPR_2021_paper.pdf)
