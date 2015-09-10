# test_classification_with_caffe
Show the classification result on shell using Caffe built in Windows 7.

How to use:
0. Build Caffe in Windows. I followed Neil Z. Shao's guide(https://initialneil.wordpress.com/2015/01/11/build-caffe-in-windows-with-visual-studio-2013-cuda-6-5-opencv-2-4-9/).
1. Open the Caffe Visual Studio project.
2. Replace tools/caffe.cpp with _test_recorder\test_recorder.cpp
3. Build caffe project to create exe file.
4. Execute _my_data\test_recorder.bat.

Default data are stored in _my_data folder, while LevelDB data were created from flower images from ImageNet(Original images were removed). You can change the file names in order to test every other trained net.
