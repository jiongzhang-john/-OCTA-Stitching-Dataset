# OCTA-Stitching-Dataset

## MR2-Net: Retinal OCTA Image Stitching via Multi-Scale Representation Learning and Dynamic Location Guidance
****

## -Background: 
Optical coherence tomography angiography (OCTA) plays a crucial role in quantifying and analyzing retinal vascular diseases. However, the limited field of view (FOV) inherent in most commercial OCTA imaging systems poses a significant challenge for clinicians, restricting the possibility to analyze larger retinal regions of high resolution. Automatic stitching of OCTA scans in adjacent regions may provide a promising solution to extend the region of interest. However, commonly-used stitching algorithms face difficulties in achieving effective alignment due to noise, artifacts and dense vasculature present in OCTA images. To address these challenges, we propose a novel retinal OCTA image stitching network, named MR2-Net, which integrates multi-scale representation learning and dynamic location guidance. In the first stage, an image registration network with a progressive multi-resolution feature fusion is proposed to derive deep semantic information effectively. Additionally, we introduce a dynamic guidance strategy to locate the foveal avascular zone (FAZ) and constrain registration errors in overlapping vascular regions. In the second stage, an image fusion network based on multiple mask constraints and adjacent image aggregation (AIA) strategies is developed to further eliminate the artifacts in the overlapping areas of stitched images, thereby achieving precise vessel alignment. To validate the effectiveness of our method, we conduct a series of experiments on two delicately constructed datasets, i.e., OPTOVUE-OCTA and SVision-OCTA. Experimental results demonstrate that our method outperforms other image stitching methods and effectively generates high-quality wide-field OCTA images, achieving a structural similarity index (SSIM) score of 0.8264 and 0.8014 on the two datasets.

****
![image](https://github.com/jiongzhang-john/OCTA-Stitching-Dataset/blob/main/label1.png)
****

## -Introduction:
Our OCTA image splicing dataset contains two main stages, where the first stage is the image alignment stage, which consists of a reference image, a target image, and a label; and the second stage is the image fusion stage, which contains five sub-datasets, consisting of center, input1, input2, input3, and input4. The following shows the data composition of each stage.

![image](https://github.com/jiongzhang-john/OCTA-Stitching-Dataset/blob/main/Image%20Registration.png)

![image](https://github.com/jiongzhang-john/OCTA-Stitching-Dataset/blob/main/Image%20Fusion.png)



****

This is a public dataset for MR2-Net; the link is [here](https://zenodo.org/records/11281652). 

![image](https://github.com/jiongzhang-john/OCTA-Stitching-Dataset/blob/main/link.png)
****
