# 4.1.3 更多边缘检测

---

## sobel过滤器

sobel过滤器增加了第二行的权重，sobel过滤器比基础的由1构成的过滤器更具有健壮性。

![](/assets/413/SobelFilter.png)

上图是一个垂直sobel过滤器，如果需要水平sobel过滤器，将该过滤器旋转90°就可以了。

---

## 其他过滤器

在进行边缘检测的过程中，不必拘泥于教科书上的过滤器，可以根据实际情况自己填入这9个数字。过滤器不光可以检测水平或者垂直的边缘，还可以检测任何角度，或者更加复杂的边缘。

