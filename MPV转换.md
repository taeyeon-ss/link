【mpv】
mkv to mp4 :- fast, easy and good quality hard-subbing using mpv

easy and full mkv to mp4 converter (encoder) for ps3 and others

http://mpv.io/ 

or 

http://mpv.srsfckn.biz/

for windows

.bat in this video can be download from here 

http://drive.google.com/file/d/0BzMWtA6ewllOUWVQcFVHMXZZSTA/edit?usp=sharing
 
Basic command line:-
 
mpv "file.mkv" -o "output.mp4" --sub-ass -ofps 24000/1001 -oharddup -ovc libx264 -ovcopts preset=medium,crf=20,profile=high,level=-1

more here 

http://github.com/mpv-player/mpv/blob/master/DOCS/encoding.rst

default Subtitle will be hardsubbed in output.mp4
 
segment linking in mkv is supported, so the mp4 will be one segment with songs

and if you want Queue, you can put many mpv line and it will convert by the order

ex:-

mpv "file1.mkv" -o "output1.mp4" --sub-ass

mpv "file2.mkv" -o "output2.mp4" --sub-ass

pause
