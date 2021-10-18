#将生成的链接库存放到build目录下的lib目录中
#在build目录下生成一个lib目录用来存放链接库生成文件
SET(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)

#查找当前目录下的所有源文件
#并将所有名称 存储在变量 DIR_LIB_SRCS 
AUX_SOURCE_DIRECTORY(. DIR_LIB2_SRCS)

#生成链接库
ADD_LIBRARY(FunT STATIC ${DIR_LIB2_SRCS})
