3C: 3C.o EdgeF.o HSVF.o CircleF.o
	g++ `pkg-config --cflags opencv` -o 3C 3C.o EdgeF.o HSVF.o CircleF.o `pkg-config --libs opencv`
    
3C.o: 3C.cpp
	g++ `pkg-config --cflags opencv` -c -o 3C.o 3C.cpp `pkg-config --libs opencv`
    
EdgeF.o: EdgeF.cpp
	g++ `pkg-config --cflags opencv` -c -o EdgeF.o EdgeF.cpp `pkg-config --libs opencv`
	
HSVF.o: HSVF.cpp
	g++ `pkg-config --cflags opencv` -c -o HSVF.o HSVF.cpp `pkg-config --libs opencv`
	
CircleF.o: CircleF.cpp
	g++ `pkg-config --cflags opencv` -c -o CircleF.o CircleF.cpp `pkg-config --libs opencv`
	
	


