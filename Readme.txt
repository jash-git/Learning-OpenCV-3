《Learning OpenCV 3》學習OpenCV 3 範例/電子檔備份


GITHUH: https://github.com/jash-git/Learning-OpenCV-3

資料來源:http://www.1024ebook.com/book/7041
http://file.allitebooks.com/20170108/Learning%20OpenCV%203.pdf
https://github.com/oreillymedia/Learning-OpenCV-3_examples


Preface. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . xv
1. Overview. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1
    What Is OpenCV? 1
    Who Uses OpenCV? 2
    What Is Computer Vision? 3
    The Origin of OpenCV 6
    OpenCV Block Diagram 8
    Speeding Up OpenCV with IPP 9
    Who Owns OpenCV? 10
    Downloading and Installing OpenCV 10
    Installation 10
    Getting the Latest OpenCV via Git 13
    More OpenCV Documentation 13
    Supplied Documentation 14
    Online Documentation and the Wiki 14
    OpenCV Contribution Repository 17
    Downloading and Building Contributed Modules 17
    Portability 18
    Summary 19
    Exercises 19
2. Introduction to OpenCV. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
    Include Files 21
    Resources 22
    First Program—Display a Picture 23
    Second Program—Video 25
    Moving Around 27
    A Simple Transformation 31
    A Not-So-Simple Transformation 32
    Input from a Camera 35
    Writing to an AVI File 36
    Summary 38
    Exercises 38
3. Getting to Know OpenCV Data Types. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 41
    The Basics 41
    OpenCV Data Types 41
    Overview of the Basic Types 42
    Basic Types: Getting Down to Details 44
    Helper Objects 52
    Utility Functions 60
    The Template Structures 67
    Summary 68
    Exercises 69
4. Images and Large Array Types. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 71
    Dynamic and Variable Storage 71
    The cv::Mat Class: N-Dimensional Dense Arrays 72
    Creating an Array 73
    Accessing Array Elements Individually 78
    The N-ary Array Iterator: NAryMatIterator 81
    Accessing Array Elements by Block 84
    Matrix Expressions: Algebra and cv::Mat 85
    Saturation Casting 87
    More Things an Array Can Do 88
    The cv::SparseMat Class: Sparse Arrays 89
    Accessing Sparse Array Elements 90
    Functions Unique to Sparse Arrays 92
    Template Structures for Large Array Types 94
    Summary 97
    Exercises 97
5. Array Operations. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 99
    More Things You Can Do with Arrays 99
    cv::abs() 102
    cv::absdiff() 103
    cv::add() 103
    cv::addWeighted() 104
    cv::bitwise_and() 106
    cv::bitwise_not() 107
    cv::bitwise_or() 107
    cv::bitwise_xor() 108
    cv::calcCovarMatrix() 108
    cv::cartToPolar() 110
    cv::checkRange() 111
    cv::compare() 111
    cv::completeSymm() 112
    cv::convertScaleAbs() 112
    cv::countNonZero() 113
    cv::cvarrToMat() 113
    cv::dct() 114
    cv::dft() 115
    cv::cvtColor() 117
    cv::determinant() 119
    cv::divide() 120
    cv::eigen() 120
    cv::exp() 121
    cv::extractImageCOI() 121
    cv::flip() 122
    cv::gemm() 122
    cv::getConvertElem() and cv::getConvertScaleElem() 123
    cv::idct() 124
    cv::idft() 124
    cv::inRange() 124
    cv::insertImageCOI() 125
    cv::invert() 126
    cv::log() 126
    cv::LUT() 127
    cv::magnitude() 127
    cv::Mahalanobis() 128
    cv::max() 129
    cv::mean() 130
    cv::meanStdDev() 130
    cv::merge() 131
    cv::min() 131
    cv::minMaxIdx() 132
    cv::minMaxLoc() 133
    cv::mixChannels() 134
    cv::mulSpectrums() 136
    cv::multiply() 136
    cv::mulTransposed() 136
    cv::norm() 137
    cv::normalize() 139
    cv::perspectiveTransform() 140
    cv::phase() 141
    cv::polarToCart() 142
    cv::pow() 142
    cv::randu() 143
    cv::randn() 143
    cv::randShuffle() 144
    cv::reduce() 144
    cv::repeat() 145
    cv::scaleAdd() 146
    cv::setIdentity() 146
    cv::solve() 147
    cv::solveCubic() 148
    cv::solvePoly() 149
    cv::sort() 149
    cv::sortIdx() 149
    cv::split() 150
    cv::sqrt() 150
    cv::subtract() 152
    cv::sum() 152
    cv::trace() 152
    cv::transform() 153
    cv::transpose() 153
    Summary 154
    Exercises 154
6. Drawing and Annotating. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 157
    Drawing Things 157
    Line Art and Filled Polygons 158
    Fonts and Text 165
    Summary 167
    Exercises 167
7. Functors in OpenCV. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 169
    Objects That “Do Stuff” 169
    Principal Component Analysis (cv::PCA) 169
    Singular Value Decomposition (cv::SVD) 173
    Random Number Generator (cv::RNG) 176
    Summary 179
    Exercises 180
8. Image, Video, and Data Files. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 183
    HighGUI: Portable Graphics Toolkit 183
    Working with Image Files 185
    Loading and Saving Images 185
    A Note About Codecs 188
    Compression and Decompression 188
    Working with Video 189
    Reading Video with the cv::VideoCapture Object 190
    Writing Video with the cv::VideoWriter Object 196
    Data Persistence 198
    Writing to a cv::FileStorage 198
    Reading from a cv::FileStorage 200
    cv::FileNode 201
    Summary 204
    Exercises 204
9. Cross-Platform and Native Windows. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 207
    Working with Windows 207
    HighGUI Native Graphical User Interface 208
    Working with the Qt Backend 220
    Integrating OpenCV with Full GUI Toolkits 232
    Summary 247
    Exercises 247
10. Filters and Convolution. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 249
    Overview 249
    Before We Begin 249
    Filters, Kernels, and Convolution 249
    Border Extrapolation and Boundary Conditions 251
    Threshold Operations 255
    Otsu’s Algorithm 258
    Adaptive Threshold 259
    Smoothing 261
    Simple Blur and the Box Filter 262
    Median Filter 265
    Gaussian Filter 266
    Bilateral Filter 267
    Derivatives and Gradients 269
    The Sobel Derivative 269
    Scharr Filter 272
    The Laplacian 273
    Image Morphology 275
    Dilation and Erosion 276
    The General Morphology Function 281
    Opening and Closing 281
    Morphological Gradient 285
    Top Hat and Black Hat 287
    Making Your Own Kernel 289
    Convolution with an Arbitrary Linear Filter 290
    Applying a General Filter with cv::filter2D() 291
    Applying a General Separable Filter with cv::sepFilter2D 292
    Kernel Builders 292
    Summary 294
    Exercises 294
11. General Image Transforms. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 299
    Overview 299
    Stretch, Shrink, Warp, and Rotate 299
    Uniform Resize 300
    Image Pyramids 302
    Nonuniform Mappings 306
    Affine Transformation 308
    Perspective Transformation 313
    General Remappings 316
    Polar Mappings 317
    LogPolar 318
    Arbitrary Mappings 322
    Image Repair 323
    Inpainting 324
    Denoising 325
    Histogram Equalization 328
    cv::equalizeHist(): Contrast equalization 331
    Summary 331
    Exercises 332
12. Image Analysis. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 335
    Overview 335
    Discrete Fourier Transform 336
    cv::dft(): The Discrete Fourier Transform 336
    cv::idft(): The Inverse Discrete Fourier Transform 339
    cv::mulSpectrums(): Spectrum Multiplication 339
    Convolution Using Discrete Fourier Transforms 340
    cv::dct(): The Discrete Cosine Transform 342
    cv::idct(): The Inverse Discrete Cosine Transform 343
    Integral Images 343
    cv::integral() for Standard Summation Integral 346
    cv::integral() for Squared Summation Integral 346
    cv::integral() for Tilted Summation Integral 346
    The Canny Edge Detector 347
    cv::Canny() 349
    Hough Transforms 349
    Hough Line Transform 349
    Hough Circle Transform 354
    Distance Transformation 358
    cv::distanceTransform() for Unlabeled Distance Transform 359
    cv::distanceTransform() for Labeled Distance Transform 360
    Segmentation 360
    Flood Fill 361
    Watershed Algorithm 365
    Grabcuts 366
    Mean-Shift Segmentation 368
    Summary 370
    Exercises 371
13. Histograms and Templates. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 373
    Histogram Representation in OpenCV 376
    cv::calcHist(): Creating a Histogram from Data 377
    Basic Manipulations with Histograms 380
    Histogram Normalization 380
    Histogram Threshold 380
    Finding the Most Populated Bin 380
    Comparing Two Histograms 382
    Histogram Usage Examples 385
    Some More Sophisticated Histograms Methods 388
    Earth Mover’s Distance 389
    Back Projection 394
    Template Matching 397
    Square Difference Matching Method (cv::TM_SQDIFF) 399
    Normalized Square Difference Matching Method
    (cv::TM_SQDIFF_NORMED) 400
    Correlation Matching Methods (cv::TM_CCORR) 400
    Normalized Cross-Correlation Matching Method
    (cv::TM_CCORR_NORMED) 400
    Correlation Coefficient Matching Methods (cv::TM_CCOEFF) 400
    Normalized Correlation Coefficient Matching Method
    (cv::TM_CCOEFF_NORMED) 401
    Summary 404
    Exercises 404
14. Contours. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 407
    Contour Finding 407
    Contour Hierarchies 408
    Drawing Contours 413
    A Contour Example 414
    Another Contour Example 416
    Fast Connected Component Analysis 417
    More to Do with Contours 420
    Polygon Approximations 420
    Geometry and Summary Characteristics 421
    Geometrical Tests 428
    Matching Contours and Images 429
    Moments 429
    More About Moments 431
    Matching and Hu Moments 435
    Using Shape Context to Compare Shapes 436
    Summary 441
    Exercises 442
15. Background Subtraction. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 445
    Overview of Background Subtraction 445
    Weaknesses of Background Subtraction 446
    Scene Modeling 447
    A Slice of Pixels 447
    Frame Differencing 451
    Averaging Background Method 452
    Accumulating Means, Variances, and Covariances 458
    A More Advanced Background Subtraction Method 467
    Structures 470
    Learning the Background 472
    Learning with Moving Foreground Objects 474
    Background Differencing: Finding Foreground Objects 475
    Using the Codebook Background Model 477
    A Few More Thoughts on Codebook Models 477
    Connected Components for Foreground Cleanup 477
    A Quick Test 481
    Comparing Two Background Methods 483
    OpenCV Background Subtraction Encapsulation 485
    The cv::BackgroundSubtractor Base Class 485
    KaewTraKuPong and Bowden Method 486
    Zivkovic Method 488
    Summary 490
    Exercises 491
16. Keypoints and Descriptors. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 493
    Keypoints and the Basics of Tracking 493
    Corner Finding 494
    Introduction to Optical Flow 498
    Lucas-Kanade Method for Sparse Optical Flow 500
    Generalized Keypoints and Descriptors 511
    Optical Flow, Tracking, and Recognition 513
    How OpenCV Handles Keypoints and Descriptors, the General Case 514
    Core Keypoint Detection Methods 526
    Keypoint Filtering 571
    Matching Methods 573
    Displaying Results 580
    Summary 583
    Exercises 584
17. Tracking. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 587
    Concepts in Tracking 587
    Dense Optical Flow 588
    The Farnebäck Polynomial Expansion Algorithm 589
    The Dual TV-L1
     Algorithm 592
    The Simple Flow Algorithm 596
    Mean-Shift and Camshift Tracking 600
    Mean-Shift 601
    Camshift 604
    Motion Templates 605
    Estimators 613
    The Kalman Filter 615
    A Brief Note on the Extended Kalman Filter 633
    Summary 634
    Exercises 634
18. Camera Models and Calibration. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 637
    Camera Model 638
    The Basics of Projective Geometry 641
    Rodrigues Transform 643
    Lens Distortions 644
    Calibration 648
    Rotation Matrix and Translation Vector 650
    Calibration Boards 652
    Homography 660
    Camera Calibration 665
    Undistortion 677
    Undistortion Maps 678
    Converting Undistortion Maps Between Representations with
    cv::convertMaps() 679
    Computing Undistortion Maps with cv::initUndistortRectifyMap() 680
    Undistorting an Image with cv::remap() 682
    Undistortion with cv::undistort() 683
    Sparse Undistortion with cv::undistortPoints() 683
    Putting Calibration All Together 684
    Summary 687
    Exercises 688
19. Projection and Three-Dimensional Vision. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 691
    Projections 692
    Affine and Perspective Transformations 694
    Bird’s-Eye-View Transform Example 695
    Three-Dimensional Pose Estimation 700
    Pose Estimation from a Single Camera 700
    Stereo Imaging 703
    Triangulation 704
    Epipolar Geometry 708
    The Essential and Fundamental Matrices 710
    Computing Epipolar Lines 720
    Stereo Calibration 721
    Stereo Rectification 726
    Stereo Correspondence 737
    Stereo Calibration, Rectification, and Correspondence Code Example 752
    Depth Maps from Three-Dimensional Reprojection 759
    Structure from Motion 761
    Fitting Lines in Two and Three Dimensions 762
    Summary 765
    Exercises 766
20. The Basics of Machine Learning in OpenCV. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 769
    What Is Machine Learning? 770
    Training and Test Sets 770
    Supervised and Unsupervised Learning 771
    Generative and Discriminative Models 773
    OpenCV ML Algorithms 774
    Using Machine Learning in Vision 776
    Variable Importance 778
    Diagnosing Machine Learning Problems 779
    Legacy Routines in the ML Library 785
    K-Means 786
    Mahalanobis Distance 793
    Summary 797
    Exercises 797
21. StatModel: The Standard Model for Learning in OpenCV. . . . . . . . . . . . . . . . . . . . . . . . . 799
    Common Routines in the ML Library 799
    Training and the cv::ml::TrainData Structure 802
    Prediction 809
    Machine Learning Algorithms Using cv::StatModel 810
    Naïve/Normal Bayes Classifier 810
    Binary Decision Trees 816
    Boosting 830
    Random Trees 837
    Expectation Maximization 842
    K-Nearest Neighbors 846
    Multilayer Perceptron 849
    Support Vector Machine 859
    Summary 870
    Exercises 871
22. Object Detection. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 875
    Tree-Based Object Detection Techniques 875
    Cascade Classifiers 876
    Supervised Learning and Boosting Theory 879
    Learning New Objects 888
    Object Detection Using Support Vector Machines 897
    Latent SVM for Object Detection 898
    The Bag of Words Algorithm and Semantic Categorization 901
    Summary 907
    Exercises 907
23. Future of OpenCV. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 909
    Past and Present 909
    OpenCV 3.x 910
    How Well Did Our Predictions Go Last Time? 911
    Future Functions 912
    Current GSoC Work 913
    Community Contributions 915
    OpenCV.org 916
    Some AI Speculation 917
    Afterword 920
A. Planar Subdivisions. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 923
B. opencv_contrib. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 939
C. Calibration Patterns. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 943
Bibliography. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 949
Index. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 967