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
