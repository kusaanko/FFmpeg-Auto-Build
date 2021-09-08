# FFmpeg-Auto-Build
This project uses GitHub Actions.  
The FFmpeg auto-build runs every Sunday and Wednesday at 4 am UTC time.  

I decided to unsupport ffmpeg 4.4 auto build because ffmpeg throws errors because of their dependencies changes and there is no advantage to use ffmpeg 4.4. It is better to use latest version of ffmpeg.

# Which asset should I download?
This is an example of an asset name.  

```
win32-ffmpeg-gpl-master-shared
```
 - win32 -- This shows the type of system. win32 is Windows 32bit. win64 is Windows 64bit.
 - gpl -- This shows license. There are two licenses - gpl and lgpl. gpl includes encoders and decoders more than lgpl.
 - master -- This shows ffmpeg's version. master means latest version.
 - shared -- This shows package type. shared includes .dll files. If it is static build, there is no strings.

# Tools used
- GitHub Actions
- ffmpeg-windows-build-helpers - https://github.com/rdp/ffmpeg-windows-build-helpers
- customized ffmpeg-windows-build-helpers - https://github.com/kusaanko/ffmpeg-windows-build-helpers