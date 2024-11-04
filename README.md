# ffmpeg-builder-psy


Here are binaries for ffmpeg statically built with a daily git pull of svt-av1-psy.

The configure is 

```
./configure   --extra-cflags="-I$HOME/ffmpeg_build/include" --extra-ldflags="-L$HOME/ffmpeg_build/lib" --extra-libs="-lpthread -lm" --enable-gpl --enable-libx264 --enable-libx265 --enable-libvpx --enable-libfdk-aac --enable-libmp3lame --enable-libopus --enable-libvorbis --enable-libass --enable-libsvtav1 --enable-libaom --enable-libdav1d --enable-nonfree --enable-static --pkg-config-flags="--static" --disable-shared
```
