
find . -name "*.png" -exec optipng -o7 {} \;
optipng -o2 -strip all <image.png>


find . -name "*.jpg" -exec jpegoptim -m60 -o -p -n --strip-all {} \;
find . -name "*.jpg" -exec jpegoptim -m60 -o -p --strip-all {} \;
find public -name "*.png" -exec open -a ImageOptim.app {} \;
