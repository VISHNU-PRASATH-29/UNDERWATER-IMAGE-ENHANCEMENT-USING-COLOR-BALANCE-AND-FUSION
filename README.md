### **_AUTHORS_**

1. VISHNU PRASATH S (vishnuselvakumar2020@gmail.com)
2. PUGAZHENTHI K (puzpuzpugazh@gmail.com)

### **ABSTRACT**

Underwater images when captured for different applications and analysis, they are degraded in quality and visual parameter; also there is sometimes information loss. Here the paper presents the methodology to improve the quality of underwater images which has been degraded due different distortions like noise, light, motion blur, scattering, waves of water, color change etc. The first approach is to implement white balance for reducing color cast efficiently and Enhancing the underwater images called mixture Contrast Limited Adaptive Histogram Equalization (CLAHE) color model. The RGB and HSV colour models are operated on using CLAHE, and the Euclidean norm is utilised to merge the two results. The combined results outperform alternative underwater picture enhancement techniques in terms of peak signal to noise ratio (PSNR) and mean square error (MSE).. It suggests that the projected technique is able to classifying coral reefs in particular while visible cues are visible. Finally the weights which are one of the ways where we restore specific required information in image for better image fusion results. After fused to overall enhance the underwater image quality thus making it more informative.


### INTRODUCTION
 
It is difficult to reconstruct an underwater item from a series of photos that have been warped by the waves of moving water. Due to the quality of the images that are acquired, underwater image processing is required. This image has blurring, distortion, and quality degradation. Waves on the surface distort images taken of underwater objects from outside the water container. Different distortions will be visible in each image if a series of photographs are taken at distinct times.Refraction causes the image captured by the camera to be warped as a result of both the amplitude of the water waves and the angle of the water surface normal at the point of refraction. There won't be any refractional distortion if the water is totally flat (i.e., there are no waves). Although, if the surface of the water is being disturbed by waves, the nature of the image distortion becomes considerably more complex. Ocean exploration and other sectors frequently use underwater imaging; nevertheless, because of environmental absorption and scattering effects, underwater images suffer substantial deterioration, primarily in the form of noise, blur, etc. The task of reconstructing an underwater image is difficult. Images taken underwater could be distorted. Both motion blur and refraction have the potential to cause distortion. Additionally, it has some quality degradation, making it necessary to raise visual quality. The quality of the photographs may be improved by reconstructing them from noisy and blurry images. It is difficult to recover the item from such distorted photos.

### IMAGE

A set of square pixels (picture elements) organised in columns and rows is called an image.. An image (from Latin: imago) is an artifact, for example a two-dimensional picture, that has a similar appearance to some subject usually a physical object or a person.
 
### IMAGE PROCESSING

Any signal processing that involves the input of an image, such as a picture or video frame, and produces either an image or a set of parameters or characteristics connected to the image is known as image processing. The majority of image-processing methods take the image as a dimensional signal and then subject it to common signal-processing methods.Although optical and analogue image processing are also feasible, digital image processing is the most common type. This article discusses universal strategies that work for all of them. Imaging refers to the process of acquiring images (creating the input image in the first place).Using image processing, one can highlight visual elements of relevance while reducing detail not essential to the purpose at hand.An image is digitalized so that it can be saved in a computer's memory or on a storage medium like a CD-ROM or hard drive. A scanner or a video camera attached to a frame grabber board in a computer can do this digitisation process. After being digitised, an image can next be subjected to a variety of image processing techniques.The three main categories of image processing activities are image compression, image enhancement and restoration, and measurement extraction. Most people are familiar with image compression. It involves lowering the memory requirement for digital image storage.Image enhancement techniques can be used to fix image flaws that may have resulted from the digitization process or from errors in the imaging setup (for example, poor lighting). The Measurement Extraction techniques can be used to extract relevant information from the image after it is in good quality.

### IMAGE ENHANCEMENT

 Image augmentation is the process of enhancing the quality of digital images (desired, for example, for visual inspection or machine analysis), without being aware of the cause of the degradation. One refers to the procedure as image restoration if the cause of the degradation is recognised. The input and output of both processes are images, making them both iconical. Images can be improved in various ways using a variety of techniques, many of which are simple and heuristic. Of course, the issue is poorly defined because there is no measurable standard for image quality. In this article, we go over a few recipes that have proven to be helpful for both human and/or machine identification. These approaches are particularly problem-focused; a strategy that succeeds in one situation could fail miserably in another. 
To accommodate for flaws in the acquisition system, early grey level changes in addition to geometric transformations may be suggested. By calibrating with the output of a picture with a constant brightness, this can be done pixel by pixel. For contrast stretching, range compression, etc., space-invariant grey value transformations are also frequently used. The grey value histogram, which represents the relative frequency of each grey value, is the crucial distribution. Digital photographs, classic photochemical photographs, illustrations, and all other types of images can be edited in many ways. Photo retouching, the process of altering images with tools like an airbrush, or modifying illustrations using any conventional artistic medium, are examples of traditional analogue image editing. Generally speaking, raster graphics editors, vector graphics editors, and other types of graphic software..

### SCOPE OF THE PROJECT

We have suggested an alternative method for improving underwater image quality. The single original image is all that is needed for our method, which is based on the fusion principle. The fundamental benefit is that our method can accurately enhance a variety of underwater photographs (from various cameras, depths, and lighting situations), recovering key faded edges and details. Additionally, the usefulness and applicability of the suggested picture enhancement method for a number of difficult underwater computer vision applications.

### LITERATURE REVIEW

	**Michele Ruta, Floriano Scioscia, Giuseppe Loseto, Eugenio Di Sciascio** presented restoration of underwater Images by fusion method. In the paper they  presented novel strategy which enhances the visibility of underwater images effectively. They have focused on image fusion which is contributed by different weight map images. The algorithm consists of different inputs mainly computed from minmax enhanced and white balanced of input distorted image[1].

	**Liming Chen; Chris Nugent, George Okeyo** presented novel strategy to enhance underwater images and videos by fusion. Their approach was first to decrease the temporal coherent noise from the image. They have also defined different weight map for videos as Laplacian contrast weight, Local contrast Weight, Saliency weight, exposed weight. Then fused image is obtained by fusion of input image with the weights[2].

	Multi sensor image fusion technique for reconstruction of images, wavelet based image fusion technique was used to get improvement in resolution of images[3].  

	It has compared different image fusion techniques with PSNR peak signal to noise ratio, EN entropy, and MSE mean squared error. Thus image fusion using wavelet transform gives better results as compared to other methods. Review results that spatial domain provide high spatial resolution, But spatial domain has image blurring problem. Wavelet transform is a very good technique for image fusion which provides high quality spectral content[4].

### EXISTING SYSTEM

Many attempts have been made to improve the visibility of such damaged photographs. Histogram equalisation appears to be severely constrained for such a work since the degradation of underwater scenes originates from the combination of multiplicative and additive processes, which make gamma correction and other classic enhancing strategies ineffective.

### DISADVANTAGES

	Existing system having number of issues that reduce their practical applicability.

	It cannot reduce color cost efficiently.

### PROPOSED SYSTEM

	In proposed system we use 3 approach. firstly, to implement white balance for reducing color cast efficiently and Enhancing the underwater images called mixture **Contrast Limited Adaptive Histogram Equalization (CLAHE)** color model.
	The method operates Contrast Limited Adaptive Histogram Equalization on **RGB and HSV color model and Euclidean norm** is used to combine both results together. 
	The combined results show **Least Mean Square Error(LMS) and high Peak Signal to Noise Ratio(PSNR)** then other methods of under water image enhancing. It shows that the projected method is capable of classifying coral reefs particularly when visual cues are visible.
	Finally the weights which are one of the ways where we restore specific required information in image for better image fusion results. After  fused to overall enhance the underwater image quality thus making it more informative.
