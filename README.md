Automated detection of surface defects plays a critical role in the timely maintenance of planar material-based products from vehicles such as cars and airplanes. Traditionally, skilled individuals have detected surface defects by visually comparing product surfaces to predefined quality standards, which is inadequate for modern industrial production because of its reliance on subjective human assessments and unquantified perception standards. Automated Visual Inspection System (AVIS), through the development of computer vision (CV)-based methods, has emerged as an alternative to significantly improve the quality of inspection through reliable defect detection approaches. CV-based surface defect detection systems, however, are dependent on a large number of defect datasets, which are crucial to training high performing and robust defect detection models. Existing benchmark datasets used in training these models are relatively small in size, deficient in defect diversity, and restricted to a relatively small number of defect categories. In this paper, we propose a novel benchmark dataset, the NCAT12-DET, a comprehensive surface defect dataset that was collected on cars. It comprises 7,200 high-resolution images across 12 distinct defect categories with a total of 23,766 bounding-box annotations. Experimental results through a comparative analysis of object detection models on the NCAT12-DET dataset demonstrated that VarifocalNet outperformed the other models with an average precision (AP) of $0.329\%$. VarifocalNet also exhibited a computational profile with 415.1 GFLOPs and 98.07M PARAMS, placing it in a comparable range to Faster R-CNN and highlighting its balanced model with reasonable computational cost.

Cite this paper using the reference below 
"**Gyimah, Nana Kankam, Robert Akinie, Xuyang Yan, Mahmoud Nabil, Kishor Datta Gupta, Abdollah Homaifar, Vahid Hemmati, and Daniel Opoku. "NCAT12-DET: A New Benchmark Dataset for Surface Defect Detection and a Comparative Study." IEEE Access (2024).**"
