Xilinx MALI repo for EGL / OpenGLES binaries and headers
=======
This repository is to include EGL / OpenGLES binaries built from the MALI
source code.

Directory structure
=======
The directory structure is organized as below:
```
|-- top
    |-- release_a (ex, r4p1-01rel0)
    |-- release_b (ex, r5p0-01rel0)
    |-- release_c (ex, r5p1-01rel0)
        |-- platform_a (ex, fbdev)
        |-- platform_b (ex, x11)
            |-- usr
                |-- include
                |-- lib
```

Headers and libraries for each platform are placed in include and lib
directories accordingly. Whenever there's a new release, a new release
directory is created with directories for available platforms.
