ROOTDIR    := /usr/local/cuda/
LIBDIR    := -L$(ROOTDIR)/lib64/ -lOpenCL
# Includes
INCLUDES  += -I$(ROOTDIR)/include -I./ 

LINK = g++  -g 

TARGET = test
SRCS = ../init.cpp test.cpp 
$(TARGET):
	$(LINK) -o $@ $(INCLUDES) $(SRCS) $(LIBDIR) -O3 
clean:
	rm -f $(TARGET) 

