# Classification of Skin Lessions using Convolutional Neural Networks
<b>Authors</b>:  Adria Romero López, Jack Burdick, Janet Weinthal, Adam Lovett <br>
<b>Advisor</b>:  Professor Oge Marques 

<b>Motivation</b>: Skin cancer is an increasingly prevalent threat. When left undiagnosed, melanoma is a particularly fatal form of skin cancer. In the United States alone, there are an estimated 76,380 new cases of melanoma and an estimated 6,750 deaths in 2016 (Siegel, Miller, & Jemal, 2016). Despite a variety of heuristic classification methods (Argenziano et al., 1998; Nachbar et al., 1994), physicians often misdiagnose skin cancer and melanomas (Kittler, Pehamberger & Binder, 2002). These heuristic diagnostic methods are fallible, and physicians instead often rely upon their previous experience and the pattern of lesions on each particular patient to classify lesions (Gachon et al., 2005). Unaided clinical diagnosis has an accuracy of only 65 - 80% (Argenziano & Soyer, 2001). Diagnostic accuracy increases by 49% when expert physicians utilize dermoscopic images of skin lesions (Kittler, Pehamberger & Binder, 2002). An intelligent tool capable of analyzing dermoscopic images and detecting potential cases of melanoma could be extremely valuable to medical experts and potentially save numerous lives each year.

<b>Methods</b>: Deep neural networks (DNNs), a form of artificial intelligence, have been shown to accurately segment and classify malignancies in medical images (Greenspan, van Ginneken, & Summers 2016). DNNs have been used to analyze dermoscopic images and classify between melanomas and atypical or benign skin lesions with an accuracy of 92.3% (Codella et al., 2015).

<b>Proposed procedure</b>: In this work we propose to advance the state of the art in two significant ways: (i) by designing, implementing, and testing intelligent solutions that use macroscopic (i.e., non-dermoscopic) images as input; and (ii) by extending the use of DNNs to the skin lesion segmentation problem. The motivation for (i) is due to dermatologists’ (and their assistants’) routine use of conventional cameras to take images of patients’ lesions using conventional cameras, a method that is less costly than the alternative -- dermoscopy -- which requires specialized equipment (Argenziano & Soyer, 2001). There is a large and ever growing amount of image data that can be used for training and testing our methods. The use of DNNs for the problem outlined in (ii) would represent a novel way of approaching the skin lesion segmentation problem from a machine learning viewpoint, in which DNNs would be used to learn which pixels belong (or not) to the region of interest (i.e., the lesion) within the image. In summary, the intended purpose of the proposed research is to design a proof-of-concept solution to automatically segment and classify macroscopic images of pigmented skin lesions.

<b>Setting up the programing environment</b>:
1. Create a separate Python virtual environment



