To build the debian package, assuming prerequisites are already installed (including glc_lib):

```
git archive -o ../glcplayer_2.3.0.orig.tar.gz HEAD
dpkg-buildpackage
```
