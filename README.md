# Simplified Menu GUI with CImg library (Dev Cpp IDE)


## Dev Cpp IDE related ERROR

C:\Users\Student\AppData\Local\Temp\ccD0ztlZ.o	CImg_demo.cpp:(.text$_ZN12cimg_library11CImgDisplay5paintEv[_ZN12cimg_library11CImgDisplay5paintEv]+0xb7): undefined reference to `__imp_SetDIBitsToDevice'

## SOLUTION:
Go to:
```
Tools >> Compiler Options >> 
```

Check Add the following commands
```
-O2 -lgdi32 
```
