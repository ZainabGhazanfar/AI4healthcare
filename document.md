
<h1> AI for healthcare: Summary</h1>

sumamry...
                                                                                                                      
<h2> Deep Learning in Medicine </h2>

<h2>Natural Language Processing (NLP) in Healthcare </h2>

<h2> AI in Diagnostics and Imaging</h2> 


Glaucoma is the disease that affects the human eye and results in a permanent blindness if not detect at early stage. The Situation is very complex, so the proper
detection is must. Detection at early stages may be improved else it may lead toloss
of vision. The main reason for the vision loss is affected optic nerve of the eye. The doctor needs at least 5 check-up reports to confirm the glaucoma a ffection, soit
becomes essential to design a system to detect this disease accurately in one attempt. This paper presents architecture for the proper glaucoma detection based ontheconvolutional neural network (CNN). It will make differentiation between the patterns
formed for glaucoma and non-glaucoma. CNN used for achieving the adequateperformance in the glaucoma detection. Overall Architecture is having six layers for
proper detection of the disease. A dropout mechanism is also applied to improve theperformance of the given approach. SCES(has 46 images for glaucoma and 1676images for the normal fundus.) and ORIGA(having 168 glaucoma and 482 images of
the normal fundus) datasets used for the experiments and obtained values are .822and .882 for the ORIGA and SCES respectively. The major objective is to findthemost similar patterns in between the normal human eye and the infected glaucomaeye. The presented approach works in six layers. The four layers are the convolutional
layers, and the last two layers are fully connected. Presented CNN to get the input, theROI of the image is used instead of full image for the Faster processing comparedtofull disc or cup images and Improved detection speed for glaucoma. Also used ARGA LI Approach (Adaptive Region Growing and Level Set Integration)
for the removal of bright fringe to improve image quality also helps determine thecenter and radius for trimming as well as fixed to 256 x 256 pixels for consistency. Dropout Implemented in two fully connected layers. To prevent overfitting, dataaugmentation generates translations and horizontal reflections of images. The areaunder the curve () AUC is utilised of the receiver operating characteristics (ROC)
curve for the evaluation of glaucoma detecting performance of the model. For validating the proposed CNN-based approach for glaucoma detection, it was
compared with state-of-the-art reconstruction-based methods. The model was trainedon 90 images from a 600-image dataset, and the remaining images were usedfor
testing. The proposed method achieved an AUC of 0.822 for the ORIGAdataset and0.882 for the SCES dataset, The state-of-the-art method, achieved an AUCs of 0.809and 0.859, respectively. The detection capability of the proposed systemseems higher
than other methods and effective for glaucoma detection [1]

<h2> AI in Diagnostics and Imaging </h2>
Medical image segmentation is a critical foundation for the advancement of healthcare systems, playing an essential role in accurately diagnosing diseases and planning treatment strategies. Among segmentation models, the U-Net architecture, a U-shaped convolutional neural network (CNN), has become a widely accepted standard due to its success in various medical image segmentation tasks. U-Net’s encoder-decoder structure allows it to capture both global and local features, but it often struggles with modeling long-range dependencies due to the intrinsic locality of its convolution operations, which primarily focus on neighboring pixels. This limitation can restrict U-Net’s ability to recognize broader contextual information, which is often crucial for precise segmentation in complex medical images. Transformers, originally designed for tasks involving sequence-to-sequence prediction, have gained popularity as potential alternatives in segmentation tasks, as their self-attention mechanism captures global dependencies across the input. However, the Transformer architecture tends to lose some fine-grained localization, as its strength in capturing long-range dependencies comes at the expense of some low-level detail accuracy. In this work, introduce TransUNet, a hybrid model that merges the strengths of both Transformers and U-Net, creating a powerful solution for medical image segmentation. TransUNet leverages Transformers to process tokenized image patches derived from CNN feature maps, effectively capturing global context and long-range dependencies. Simultaneously, it incorporates U-Net’s decoder to upsample the encoded features and combine them with high-resolution CNN feature maps, thereby restoring precise localization and low-level details. This combination allows TransUNet to capitalize on the Transformer’s global feature extraction while preserving U-Net’s ability to enhance spatial detail and segmentation accuracy. TransUNet consistently outperforms other methods across various medical segmentation applications, including multi-organ segmentation and cardiac segmentation, highlighting its effectiveness in improving segmentation outcomes through its innovative, dual-component design.
<h2>AI in Drug Discovery and Development </h2> 

<h2> Robotics and AI in Surgery </h2>

<h2>AI in Patient Monitoring and Management </h2>

<h2>Ethical Considerations and Bias in AI </h2>

<h2>AI and Healthcare Policy </h2>

<h2>Case Studies and Real-World Applications </h2>

<h2> Future Directions and Course Wrap-Up </h2>

<h2> References</h2>
[1] Arkaja Saxena, Abhilasha Vyas, Lokesh Parashar, Upendra Singh, A Glaucoma Detection using Convolution Neural Network 
