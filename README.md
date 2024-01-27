# ViewSDimageInNewTab
 This guide shows you how to view sd images in a new tab and refresh automagically ( automatic1111 )

* Edit stable-diffusion-webui\modules\images.py as below <br>
```
file_path_temp = "E:\git_projx\stable-diffusion-webui\outputs\currimg.png" #change this to whatever you want
image.save(file_path_temp)
```

![screenshot](media\edited_file.png)<br><br>
* Save the Index.html file ,and edit the path to the image in there accrdingly too <br>
* Enjoy !!!! <br>
* I know this is a fugly way to do it, but until it's added in to automatic1111 webui, you can use this. 