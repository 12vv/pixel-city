# Pixel City

## Description
基于 WebGL, three.js 实现的将图片根据像素值出现的频率体素化，并做三维展示。
- 若导入的图片过大，会调整大小后再计算，以免渲染卡顿。
- 图片某些像素值会占主导地位，造成最后做范围映射时其他像素频率区别不大，所以规定一个最大像素值再进行范围映射。

Implements to voxelize the image according to the frequency of pixel values and render for 3D interaction using based on WebGL, three.js.
- If the imported image is too large, it will be resized and then calculated to avoid rendering lag.
- Some pixel values of the image will dominate and cause little difference in the frequency of other pixels when the final range mapping is done, so a maximum pixel value is specified before range mapping.

![screenshot](https://github.com/12vv/12vv.github.io/blob/master/images/proj/PIXELCITY.png)

## Usage
Need a live server to start.
Or go to [demo](https://12vv.github.io/projects/pixelcity.html) to try out!
