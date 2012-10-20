http://poppler.freedesktop.org

```
vulcan build -v \
    -d $FONTCONFIG_PACKAGE_TGZ \
    -n poppler \
    -c "./configure --prefix /app/vendor/poppler --disable-static \
        --enable-zlib && make install" \
    -p /app/vendor/poppler
```

