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


目錄

譯者序       xvii

前言         xxi

第1章 概述      1

什么是OpenCV        1

OpenCV怎么用        2

什么是計算機視覺     3

OpenCV的起源        6

OpenCV的結搆    7

使用IPP來加速OpenCV     8

誰擁有OpenCV    9

下載和安裝OpenCV    9

安裝             9

從Git獲取最新的OpenCV      12

更多的OpenCV文檔   13

提供的文檔      13

在線文檔和維基資源     13

OpenCV貢獻庫       15

下載和編譯Contributed模塊         16

可移植性           16

小結  17

練習  17

第2章OpenCV初探            19

頭文件    19

資源           20

第一個程序：顯示圖片       21

第二個程序：視頻    23

跳轉  24

簡單的變換          28

不那么簡單的變換    30

從攝像頭中讀取      32

寫入AVI文件        33

小結  34

練習  35

第3章 了解OpenCV的數據類型    37

基礎知識           37

OpenCV的數據類型   37

基礎類型概述    38

深入了解基礎類型       39

輔助對象        46

工具函數        53

模板結搆        60

小結  61

練習  61

第4章 圖像和大型數組類型       63

動態可變的存儲      63

cv::Mat類N維稠密數組         64

創建一個數組    65

獨立獲取數組元素       69

數組迭代器NAryMatIterator         72

通過塊訪問數組元素     74

矩陣表達式：代數和cv::Mat         75

飽和轉換        77

數組還可以做很多事情    78

稀疏數據類cv::SparesMat  79

訪問稀疏數組中的元素    79

稀疏數組中的特有函數    82

為大型數組准備的模板結搆         83

小結  85

練習  86

第5章 矩陣操作  87

矩陣還可以做更多事情       87

cv::abs()        90

cv::add()        91

cv::addWeighted()        92

cv::bitwise_and()  94

cv::bitwise_not() 94

cv::bitwise_or()   94

cv::bitwise_xor()  95

cv::calcCovarMatrix()     95

cv::cartToPolar()  97

cv::checkRange()  97

cv::compare()    98

cv::completeSymm()      99

cv::convertScaleAbs()     99

cv::countNonZero()      100

cv::Mat cv::cvarrToMat() 100

cv::dct()        101

cv::dft()        102

cv::cvtColor()   103

cv::determinant()        106

cv::divide()     106

cv::eigen()      106

cv::exp()       107

cv::extractImageCOI()    107

cv::flip()       108

cv::gemm()     108

cv::getConvertElem()和cv::getConvertScaleElem()     109

cv::idct()       110

cv::inRange()    110

cv::insertImageCOI()      111

cv::invert()      111

cv::log()        112

cv::LUT()      112

cv::Mahalanobis()       113

cv::max()       114

cv::mean()      115

cv::meanStdDev()       116

cv::merge()     116

cv::min()       116

cv::minMaxIdx()       117

cv::minMaxLoc()        118

cv::mixChannels()       119

cv::mulSpectrums()      120

cv::multiply()   121

cv::mulTransposed()     121

cv::norm()      122

cv::normalize()  123

cv::perspectiveTransform()          125

cv::phase()      125

cv::polarToCart()        126

cv::pow()       126

cv::randu()      127

cv::randn()      127

cv::repeat()     129

cv::scaleAdd()   129

cv::setIdentity()  130

cv::solve()      130

cv::solveCubic()        131

cv::solvePoly()  132

cv::sort()       132

cv::sortIdx()     133

cv::split()       133

cv::sqrt()       134

cv::subtract()    135

cv::sum()       135

cv::trace()      135

cv::transform()   136

cv::transpose()   136

小結137

練習137

第6章 繪圖和注釋             139

繪圖139

藝朮線條和填充多邊形   140

字體和文字     146

小結148

練習148

第7章OpenCV中的函數子      151

操作對象          151

主成分分析（cv::PCA）  151

奇異值分解cv::SVD     154

隨機數發生器cv::RNG   157

小結160

練習160

第8章 圖像、視頻與數據文件    163

HighGUI模塊：一個可移植的圖形工具包163

圖像文件的處理     164

圖像的載入與保存      165

關於codecs的一些注釋   167

圖片的編碼與解碼      168

視頻的處理         169

使用cv::VideoCapture對象讀取視頻流    169

使用cv::VideoWriter對象寫入視頻   175

數據存儲          176

cv::FileStorage的寫入    177

使用cv::FileStorage讀取文件        179

cv::FileNode    180

小結183

練習183

第9章 跨平台和Windows系統    187

基於Windows開發   187

HighGUI原生圖形用戶接口         188

通過Qt后端工作        199

綜合OpenCV和全功能GUI工具包    209

小結222

練習222

第10章 濾波與卷積            225

概覽225

預備知識          225

濾波、核和卷積        225

邊界外推和邊界處理    227

閾值化操作         230

Otsu算法       233

自適應閾值     233

平滑235

簡單模糊和方框型濾波器          236

中值濾波器     238

高斯濾波器     239

雙邊濾波器     240

導數和梯度         242

索貝爾導數     242

Scharr濾波器    244

拉普拉斯變換   245

圖像形態學         246

膨脹和腐蝕     247

通用形態學函數        250

開操作和閉操作        251

形態學梯度     254

頂帽和黑帽     256

自定義核       258

用任意線性濾波器做卷積    259

用cv::filter2D()進行卷積  259

通過cv::sepFilter2D使用可分核      260

生成卷積核     260

小結262

練習262

第11章 常見的圖像變換        267

概覽267

拉伸、收縮、扭曲和旋轉    267

均勻調整       268

圖像金字塔     269

不均勻映射     273

仿射變換       274

透視變換       279

通用變換          282

極坐標映射     282

LogPolar       283

任意映射       287

圖像修復          287

圖像修復       288

去噪          289

直方圖均衡化       292

cv::equalizeHist()用於對比均衡      294

小結295

練習295

第12章 圖像分析    297

概覽297

離散傅里葉變換     297

cv::dft()離散傅里葉變換  298

cv::idft()用於離散傅里葉逆變換     300

cv::mulSpectrums()頻譜乘法        300

使用傅里葉變換進行卷積          301

cv::dct()離散余弦變換   303

cv::idct()離散余弦逆變換           304

積分圖   304

cv::integral()標准求和積分         306

cv::integral()平方求和積分         306

cv::integral()傾斜求和積分         307

Canny邊緣檢測     307

cv::Canny()     309

Hough變換         309

Hough線變換   309

Hough圓變換   313

距離變換          316

cv::distanceTransform()無標記距離變換   317

cv::distanceTransform()有標記距離變換   317

分割318

漫水填充       318

分水嶺算法     322

Grabcuts算法    323

Mean-Shift分割算法    325

小結326

練習326

第13章 直方圖和模板          329

OpenCV中直方圖的表示     331

cv::calcHist()：從數據創建直方圖   332

基本直方圖操作     334

直方圖歸一化   334

直方圖二值化   335

找出最顯著的區間      335

比較兩個直方圖        337

直方圖用法示例        339

一些復雜的直方圖方法      342

EMD距離      342

反向投影       347

模板匹配          350

方差匹配方法（cv::TM_SQDIFF）   351

歸一化方差匹配方法（cv::TM_SQDIFF_NORMED）        352

相關性匹配方法（cv::TM_CCORR）352

歸一化的互相關匹配方法（cv::TM_CCORR_NORMED）     352

相關系數匹配方法（cv::TM_CCOEFF）            352

歸一化的相關系數匹配方法（cv::TM_CCOEFF_NORMED）  352

小結355

練習355

第14章 輪廓   359

輪廓查找          359

輪廓層次       360

繪制輪廓       364

輪廓實例       365

另一個輪廓實例        366

快速連通區域分析      368

深入分析輪廓       370

多邊形逼近     370

几何及特性概括        372

几何學測試     377

匹配輪廓與圖像     378

矩   378

再論矩         380

使用Hu矩進行匹配      383

利用形狀場景方法比較輪廓        384

小結388

練習389

第15章 背景提取    391

背景提取概述       391

背景提取的缺點     392

場景建模          392

像素          393

幀間差分       396

平均背景法         397

累計均值，方差和協方差          403

更復雜的背景提取方法      410

結搆          413

進行背景學習   414

存在移動的前景物體時進行背景學習417

背景差分：檢測前景物體          418

使用碼書法的背景模型   419

關於碼書法的其他想法   419

使用連通分量進行前景清理   420

小測試         423

兩種背景方法的對比        425

OpenCV中的背景提取方法的封裝       425

cv::BackgroundSubstractor基類      426

KB方法        427

Zivkovic方法    428

小結431

練習431

第16章 關鍵點和描述子        433

關鍵點和跟蹤基礎   433

角點檢測       434

光流簡介       437

Lucas-Kanade稀疏光流法          438

廣義關鍵點和描述符        448

光流，跟蹤和識別      450

OpenCV一般如何處理關鍵點和描述符   451

核心關鍵點檢測方法    461

關鍵點過濾     497

匹配方法       499

結果顯示       505

小結508

練習508

第17章 跟蹤   511

跟蹤中的概念       511

稠密光流          512

Farneback多項式擴展算法          513

Dual TV-L1模型  515

簡單光流算法   519

Mean-Shift算法和Camshift追蹤         522

Mean-Shift算法  522

Camshift       526

運動模板          526

估計533

卡爾曼濾波器   534

擴展卡爾曼濾波器簡述   549

小結551

練習551

第18章 相機模型與標定        553

相機模型          554

射影几何基礎   556

Rodrigues變換   558

透鏡畸變       559

標定562

旋轉矩陣和平移向量    563

標定板         566

單應性         572

相機標定       576

矯正587

矯正映射       587

使用cv::convertMaps()在不同表示方式之間轉換矯正映射     588

使用cv::initUndistortRectifyMap()計算矯正映射      589

使用cv::remap()矯正圖像           591

使用cv::undistort()進行矯正        591

使用cv::undistortPoints()進行稀疏矯正    591

與標定結合         592

小結595

練習596

第19章 投影與三維視覺        599

投影600

仿射變換與透視變換        601

鳥瞰圖變換實例        602

三維姿態估計       606

單攝像機姿態估計      607

立體成像          609

三角測量       610

對極几何       613

本徵矩陣和基本矩陣    615

計算極線       624

立體校正       624

立體校正       628

立體匹配       638

立體校正、標定和對應的示例代碼   650

來自三維重投影的深度映射        657

來自運動的結搆     659

二維與三維直線擬合        659

小結662

練習662

第20章 機器學習基礎          665

什么是機器學習     665

訓練集和測試集        666

有監督學習和無監督學習          667

生成式模型和判別式模型          669

OpenCV機器學習算法   669

機器學習在視覺中的應用          671

變量的重要性   673

診斷機器學習中的問題   674

ML庫中遺留的機器學習算法  678

K均值         679

馬氏距離       684

小結687

練習687

第21章StatModel：OpenCV中的基准學習模型       689

ML庫中的常見例程  689

訓練方法和cv::ml::TrainData的結搆  691

預測          697

使用cv::StatModel的機器學習算法       698

朴素貝葉斯分類器      699

二叉決策樹     703

Boosting方法    716

隨機森林       721

期望最大化算法        725

K近鄰算法       729

多層感知機     731

支持向量機     739

小結749

練習750

第22章 目標檢測    753

基於樹的目標檢測技朮      753

級聯分類器     754

有監督學習和boosting理論         756

學習新目標     764

使用支持向量機的目標識別   772

Latent SVM用於目標識別          772

Bag of Words算法與語義分類       775

小結780

練習780

第23章OpenCV的未來         783

過去與未來         783

OpenCV 3.x     784

我們上一次預測怎么樣？    784

未來應用          785

目前GSoC的進展       787

社區貢獻       788

OpenCV.org     789

一些關於AI的猜測   790

結語793

附錄A平面划分     795

附錄B opencv_contrib模塊概述         809

附錄C標定圖案     813

參考文獻      819

https://detail.tmall.com/item.htm?spm=a230r.1.14.68.6dea79aaby6EG3&id=574723794426&ns=1&abbucket=3