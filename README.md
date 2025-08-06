# car
시간바꾸기
sudo timedatectl set-timezone 'Asia/Seoul'


한글 설치
우분투에서 ibus를 통한 한글 변환이 생각처럼 잘 안되는 경우가 많다.
그래서 fcitx를 이용하는 것이 종종 더 편하다.
아래는 fcitx를 이용해서 한글 입력 설정을 하는 내용이다.
18.04에서 설정한 내용이지만 16.04나 상위버전에도 문제없이 설치가 가능하다.
 
□ 설치 환경
   - ubuntu 18.04
   - ubuntu 20.04
   - 원격 데스크톱 수행 시 trooble shooting 
 
일단 아래와 같이 수행해서 fcitx-hangul을 설치한다. 대개의 경우... 아주 잘 설치된다.
$ sudo apt-get update$ sudo apt-get install fcitx-hangul
 
우분투 Setting에서 Region & Language 수행 - Manage installed Language 버튼 실행한다.
출처: https://driz2le.tistory.com/253 [홀로 떠나는 여행:티스토리]
