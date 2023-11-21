Digital Image Processing Tutorial (Chapter 7)
=============================================

👋 Hello and Welcome! 

 You've stumbled upon an beginner-friendly yet in-depth tutorial for **Digital Image Processing**. This repository is perfect for beginners and anyone curious about the inner workings of image processing techniques. While packages like `OpenCV` make these methods easily accessible, understanding the mechanics behind them can be both fascinating and enriching.


Chapter 7. Noise and Noise Reduction, Homomorphic and Band Stop Filter
----------------------------------------------------------------------

* Source Code available [here](https://github.com/Wilson-ZheLin/Introduction-to-Digital-Image-Processing/blob/main/7.%20Image%20Noise%20and%20Noise%20Reduction%2C%20Homomorphic%20Filter%2C%20and%20Band%20Stop%20Filter/src/main.cpp)

* Report with qualitative comparsion available [here](https://github.com/Wilson-ZheLin/Introduction-to-Digital-Image-Processing/blob/main/7.%20Image%20Noise%20and%20Noise%20Reduction%2C%20Homomorphic%20Filter%2C%20and%20Band%20Stop%20Filter/7.%20Image%20Noise%20and%20Noise%20Reduction%2C%20Homomorphic%20Filter%2C%20and%20Band%20Stop%20Filter.pdf)


Getting Started
---------------
### For MacOS:

To ensure compatibility with MacOS, update the **memory allocation header** `#include <mm_malloc.h>` to `#include <malloc.h>`:

```
#include <malloc.h>
```

### For Windows:

Windows users can retain the existing **memory allocation header**:

```
#include <mm_malloc.h>
```


### Configuring Input/Output Paths

1. **Set Input Path:** In the `main()` function, update the input image path according to your requirements.

2. **Enable Desired Functions:** In `TestReadImage()`, uncomment the functions you wish to use for image processing. Each function is documented for easy reference.

3. **Execute the Program:** Run your program to see the results.


Tutorial Preview：
-----------------

![image](../static/ch7.png)
