# ubuntu-setting

## hangul 키 세팅
- xev
- xmodmap -pke > ~/xmodmap_original
- xmodmap -pke > ~/.Xmodmap
- emacs -nw ~/.Xmodmap 
xev를 찾은 key 값을 Hangul 키로 세팅한다.
- xmodmap ~/.Xmodmap

