To build ffmpeg for android, execute following commands:<br>
<pre>
    cd src/ffmpeg<br>
    ./build_all.sh<br>
</pre>

Result files:<br>
<pre>
    bin/ffmpeg.armv5<br>
    bin/ffmpeg.armv7<br>
</pre>

Tested build environment:<br>
<pre>
    Mac OS X 10.7 64bit<br>
    Ubuntu 12 64bit<br>
    CentOS 5 64bit<br>
</pre>

Compiler:<br>
<pre>
    Android NDK r8 or r9. Gcc 4.4.3 or 4.8.
</pre>

Supported features:<br>
<pre>
    accept format: raw image, jpg, png, H264/MP4, WebM<br>
    accept protocol: pipe, file, tcp<br>
    accept filter: resize, rotate<br>
    for more details, see 9_build_ffmpeg_*.sh
</pre>