#最低的cmake版本限制
CMAKE_MINIMUM_REQUIRED(VERSION 3.1)

#项目信息
PROJECT(touwenj)

#想当前工程添加存放源文件的子目录
ADD_SUBDIRECTORY(lib/fun1)
ADD_SUBDIRECTORY(lib/fun2)
ADD_SUBDIRECTORY(src)