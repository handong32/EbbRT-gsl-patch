# EbbRT-gsl-patch

git clone git://git.savannah.gnu.org/gsl.git

then apply patches

./configure CC=x86_64-pc-ebbrt-gcc CFLAGS='-O4' CPPFLAGS='-O4' --host=x86_64-pc-ebbrt --enable-static --disable-shared --disable-dependency-tracking

