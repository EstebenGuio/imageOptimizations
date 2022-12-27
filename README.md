# EstebenGuio | Image optimizations linux system | 12272022

A very fast way to reduce syze of images without losing quality is using [tinypng](https://tinypng.com/), however this options has limited upload images and **works only on png images**.


Usin linux you can use:

> Install on debian based system 
>
> ### jpegoptim 
>
>
> `sudo apt-get install jpegoptim`
  
> ### OptiPNG 
>
>
> `sudo sudo apt-get install optipng`

## Single file

> ### For a single file:
>
> `jpegoptim image.jpg` 
> #### Or 
> `optipng image.png`

# Multiple files


> ### For a single file:
>
> `cd /your-folder-path/ && `
> ` jpegoptim *.jpg` 
> #### Or 
>
> `cd /your-folder-path/ && `
> `optipng *.png`