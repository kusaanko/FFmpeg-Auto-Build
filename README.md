# FFmpeg-Auto-Build
This project uses GitHub Actions.  

# Which asset do I download?
This is an example of an asset name.  

```
win32-ffmpeg-gpl-n4.3.1-shared
```
 - win32 -- This shows the type of system. win32 is Windows 32bit. win64 is Windows 64bit.
 - gpl -- This shows license. There are two licenses - gpl and lgpl. gpl includes encoders and decoders more than lgpl.
 - n4.3.1 -- This shows ffmpeg's version. If there is no version, it means the latest build.
 - shared -- This shows package type. shared includes .dll files. If it is static build, there is no strings.

If you are using Windows 64bit and you want to use stable version of ffmpeg, you should download win64-ffmpeg-gpl-n(version).

# Tools used
ffmpeg-windows-build-helpers - https://github.com/rdp/ffmpeg-windows-build-helpers  
Retry steps - https://github.com/marketplace/actions/retry-step
