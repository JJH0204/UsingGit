- 태그 : #Git_적응기

집에서 Windows 데스크탑과 Mac 노트북을 병행해서 사용하다 보니 작업물을 공유하는데 어려움이 있었다. 이전까지 공유를 구글 드라이브를 애용 했지만 일일 사용량(패킷)의 제한이 있다보니 프로젝트 버전 관리등 어려움이 있었는데 이 기회에 깃을 사용하면서 적응해 보려 한다. (계속 갱신 예정)
# 1. Git
*소프트웨어 개발에 주로 사용된다.*
- 파일 및 리소스(소스코드 등) 변경사항 추적에 사용
# 2. Git 설치
## 2.1. Mac OS 에서
*[왕 초보 가이드](https://sin0824.tistory.com/8)*
- - -
> Homebrew 설치
- [Homebrew 설치링크](https://brew.sh) 에서 알려주는 설명대로 터미널을 통해서 설치하는게 일반적이지만 Mac OS의 경우 [Homebrew 릴리즈 다운로더](https://github.com/Homebrew/brew/releases/latest) 로 설치하는게 마음편하다.
- 다운로더 실행 후 설정 변경없이 다음 누르기만하면 되서 편하다.
- - -
>Git 설치 및 설정
- 필요한 깃 설정들은 [amamov](https://github.com/amamov/gits#git-install-mac) 님의 깃 헙 자료를 참고해서 진행했다.
---
>Git 리모트 해제 방법
- 공유 중인 디렉토리로 이동
- 리모트 정보 확인
- 연결 이름 확인 (나 같은 경우 origin 을 사용했음)
- $ git remote remove origin 입력
- 이후 원하는 레포지토리 링크를 위 링크에서 설명한 방법대로 다시 연결하면 끝
---
> 레포지토리를 찾을 수 없습니다. (에러)
### 해결 방법 1
- 원격 저장소 정보 업데이트
- $ git remote update
### 해결 방법 2
- [레포지토리 리모트 해제 후 재연결](Git 리모트 해제 방법)
### 해결 방법 3
- [SSH 접속 설정](https://www.lainyzine.com/ko/article/creating-ssh-key-for-github/)
- [SSH 접속 설정(Windows)](https://abcdefgh123123.tistory.com/211)
---
>레포지토리 삭제(설정)
- [레포지토리 삭제 방법](https://devmango.tistory.com/53)