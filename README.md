make_ppt
========

Convert a list of images to a power point presentation.
Useful if someone decides that you have to submit you PDF presentation in Power Point format in the last second.
You can run something like:
```
convert -density 1500 -fill white -opaque none -quality 100 -resize 2000x  "5_minute_prsentation.pdf" "ims/%02d.png"
````
And then use this script:

```
python make_ppt.py
```

It requires the [python-pptx][1] library.

[1]: https://github.com/scanny/python-pptx
