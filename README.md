# argyle_manifest
Manifest to build argyle platform

### In order to build this source you need:
..*Some form of linux distro (Ubuntu is the general recommendation, but other distros will work as well).
..*To read the build documentation here:
https://source.android.com/source/initializing.html

Make your build directory with:
<pre><code> repo init -u https://github.com/saintsantos/argyle_manifest.git</code></pre>

Then download the source:
<pre><code> repo sync </code></pre>

Build the source:
<pre><code> make -j4 </code></pre>




