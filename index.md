---
layout: default
---

<h2 style="text-align: center;">Introduction</h2>
<p style="text-align: justify">This study explores the intriguing similarities between the mouse visual cortex and deep learning models, particularly in object classification tasks. By introducing a novel Neural Response Normalization (NeuRN) layer inspired by specific types of excitatory biological neurons, we have enhanced the resemblance between neural and artificial systems. This modification not only improves the similarity between the mouse visual cortex and deep learning models but also significantly bolsters performance in domain generalization tasks. The findings offer valuable insights for the development of advanced, neuro-inspired AI models, with potential widespread implications for real-world tasks.</p>

<h2 style="text-align: center;">Mouse Visual Cortex & Deep Learning Neural Networks</h2>
![Visual Cortex to Artificial Networks](Figure_1.drawio.png)
<p style="text-align: justify">Block diagram architecture of comparison framework: Image stimuli is presented to mice and DNN models (Step 1) and their corresponding feature (Step 2) and neural representations (Step 3) are computed and compared (Step 4).</p>

<h2 style="text-align: center;">Allen Brain Observatory Data</h2>
![Methods](Methods_NeurAI.png)
<p style="text-align: justify">Mouse Visual Cortex (MVC) data statistics: The peak activation profiles of all neurons are presented as well as their cluster profiling and distribution based on neural genotypes and brain regions.</p>

<h2 style="text-align: center">Feature Represntations</h2>
![Representational Similarity](Extra_Figures.drawio.png)
<p style="text-align: justify">Representational similartiy between feature detectors in a sample DNN model and MVC neural representations</p>


<h2 style="text-align: center">DNN Architectural Similarity</h2>
![Architectural Similarity](Figure_6.drawio.png)
<p style="text-align: justify">DNNs' architectural similarity: The confusion matrix on the left shows the correlation similarity of 44 DNN architectures with purple as the lowest and skin as the highest correlation. The zoom version of three similar architectures (VGG11, VGG16 and VGG19) are displayed with the highlighted layer difference between VGG16 and VGG11 as ReLU and Conv between VGG16 and VGG19. The bottom matrices show the Needleman-Wunsch algorithm applied on these architectures and how the traceback matrix was used to calculate similarity index.</p>

<h2 style="text-align: center">Population & Neuron Level Analysis</h2>
![Architectural Similarity](Figure_5.drawio.png)
<p style="text-align: justify">(a) RMSE scores of comparing feature detectors with neural representations across MVC brain regions for all the shortlisted DNN architectures, (b) shows the similar focused across neural sub-types: excitatory and inhibitory neural genotypes. The comparison between NeuRN and non-NeuRN architectures are shown in (c) with diagonal line defining the winning models for their neural compatibility. In (d), comparison of neural representations and DNN activations is mapped for both NeuRN and non-NeuRN DNN architectures, showing the activation curves of randomly sampled units in (e).</p>


<h2 style="text-align: center">Summary</h2>
<p style="text-align: justify">In this study, we explore the fascinating interplay between artificial and biological neural networks. Our work reveals a striking similarity between these systems, particularly with excitatory genotypes. To further investigate, we developed NeuRN, a neuro-inspired layer for Deep Neural Networks (DNNs), which enhances the resemblance between artificial and biological representations. Our detailed analyses at both population and single neuron levels confirmed the increased similarity and biological plausibility brought about by NeuRN. This novel layer not only boosts the generalizability and robustness of DNNs but also significantly improves performance on domain adaptation tasks, as evidenced by our experiments with Neural Architecture Search and various DNNs. In essence, our findings underscore the potential of biological mechanisms to significantly refine and advance artificial neural networks.</p>



<!-- <script type="text/javascript" src="https://viewer.diagrams.net/js/viewer-static.min.js"></script> -->
