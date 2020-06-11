# ubuntu-setting

## hangul 키 세팅 1
- xev
- xmodmap -pke > ~/xmodmap_original
- xmodmap -pke > ~/.Xmodmap
- emacs -nw ~/.Xmodmap 
xev를 찾은 key 값을 Hangul 키로 세팅한다.
- xmodmap ~/.Xmodmap

## Hangul 키 세팅 2
- /usr/share/X11/xkb/symbols/altwin 수정

## Vivado 실행용 세팅
- Error message
application-specific initialization failed: couldn't load file "librdi_commontasks.so": libtinfo.so.5: cannot open shared object file: No such file or directory

- sudo apt install libtinfo-dev
- cd /usr/lib/x86_64-linux-gnu
- sudo ln -s libtinfo.so.6 libtinfo.so.5

# mac setting

## 배터리 광탈 문제 해결

- sudo pmset standbydelaylow 600 standbydelayhigh 3600
