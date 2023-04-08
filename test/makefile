CC = clang++ -g -Wall 
APP_NAME = test
BUILD_DIR = .
C_FILES = test.cpp

APP_INCLUDES := -I../vendors/GLFW -I../vendors/GLEW -framework Cocoa -framework OpenGL -framework IOKit
APP_LINKERS := -L../vendors/GLFW/lib -L../vendors/GLEW/lib -lglfw3 -lglew

all: test.cpp
	$(CC) $(C_FILES) -o $(BUILD_DIR)/$(APP_NAME) $(APP_INCLUDES) $(APP_LINKERS)
