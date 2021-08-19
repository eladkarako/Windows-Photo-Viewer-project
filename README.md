just few notes for me:

C:\Windows\winsxs
C:\Windows\winsxs\Manifests
c:\Program Files\Windows Photo Viewer

registry values

Windows 7

Windows 10

values are full including some other stuff, don't import reg files "just like that", 
those are raw values, which includes complete data for classes and file types.

clean win10 also have it, no installation needed, just go to install windows components and scroll to bottom and mark TIFF ifilter.

`%SystemRoot%\System32\rundll32.exe "%ProgramFiles%\Windows Photo Viewer\PhotoViewer.dll", ImageView_Fullscreen %1`