## Atom 플러그인 설치

1.atom-beautify 플러그인 설치 된 상태에서 단축키 ctrl-alt-b 누르면 Rubocop 설치 하라고 나옴 이때 package install에서 linter-rubocop 검색하여 설치
2.atom-beautify setting에서 Executable > Rubocop 경로 기입 ex)C:\\Ruby26-x64\\bin\\rubocop.bat 기입
3.Atom에서 ruby 파일 선택하여 ctrl-alt-b 실행 하기 4.부가적으로 C:rubocop 폴더 생성하여 rubocop 실제 설치 해보기
5.rubocop 해당 경로 참고하여 설치 <https://docs.rubocop.org/rubocop/installation.html>

## python pip 설치/코드 정적 도구

1.pip install pep8
2.pip install pycodestyle

## VS code 플러그 인 설치

1.ruby 플러그인 모두 삭제
2.새로 ruby extension pack 설치

## 그외 Atom 추천 플러그 인

1.<https://steemit.com/kr/@k00432/markdown-atom-markdown>

## VS code 에디터 설정

[Visual Studio Code] 자동 줄바꿈 설정
1.Visual Studio 코드를 실행한다.
2.File - 기본설정(Preferences) -> Settings 에 들어간다. 파일 -> Preferences -> Settings
3.'wordWrap' 을 검색한다.
4.'On'으로 설정한다. 검색 -> On으로 설정.

## Atom

Indent Guide Improved 색상 조절
File → Stylesheet
styles.less라는 페이지창이 나옵니다.
해당 페이지에 아래 코드를 복사해서 붙여넣으면 가이드라인별 색상 조절이 가능합니다.
gray, cyan, blue로 각각 색이 설정되있습니다.
.indent-guide-improved {
  background-color: gray;
  &.indent-guide-stack {
    background-color: cyan;
    &.indent-guide-active {
     background-color: blue;
    }
  }
}

## Powershell 테마 설정 방법
1.터미널 테마 설정 <https://proni.tistory.com/entry/PowerShell-%ED%85%8C%EB%A7%88%EB%A1%9C-%EC%98%88%EC%81%98%EA%B2%8C-%EC%93%B0%EA%B8%B0-with-Windows-Terminal>
2.<https://docs.microsoft.com/ko-kr/windows/terminal/tutorials/powerline-setup>
3.<https://daddyprogrammer.org/post/14536/windows-powershell-oh-my-posh/>

## Powershell 권한 설정 오류 발생시 처리 방법
이 시스템에서 스크립트를 실행할 수 없으므로 C:\Users\shimk\AppData\Roaming\npm\webpack.ps1 파일을 로드할 수 없습니다.
<https://dog-developers.tistory.com/m/183>