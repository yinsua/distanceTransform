## distanceTransform
距离变换

####注：通常在使用cvDistTransform之后可能会直接imshow矩阵，此时得到的通常和canny算子得到的一样，但实际上是不同的，可以通过查看矩阵元素得知。出现这种现象是因为格式的差异，因此你需要在做完距离变换之后加入格式转换：dist32s.convertTo(dist8u1, CV_8U, 1, 0);
