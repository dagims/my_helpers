CMAKE_MINIMUM_REQUIRED (VERSION 2.8 )
PROJECT(TrainDlibSP)
FIND_PACKAGE(dlib REQUIRED)
ADD_EXECUTABLE( train_sp train_shape_predictor.cpp)
TARGET_LINK_LIBRARIES(train_sp dlib::dlib)
