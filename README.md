#bxp syntax definition for sublime text 2

북잼의 전자책 포맷인 BXP(Bookjam eXtensible Publication)를 sublime text 에서 사용하기 위한 syntax definition 입니다.
기준 파일은 sbml, sbss, bon 3가지 대표적인 파일을 지원합니다.
sublime text 2 기준으로 작성했으며 지속적으로 업데이트할 예정입니다.

원래 package 로 만들어서 사용해야 되는데 어느정도 완성되고 난뒤에 그렇게 배포할 예정!
package repository 가 따로 있는것으로 보임.

## sublime text 2 에서 사용하기
1. "Package Control" 설치 : https://packagecontrol.io/installation#st2
2. "Package Install" 을 이용해 "AAAPackageDev" 패키지 설치
3. "Tools > Packages > Package Development > New Syntax Definition" 으로 새 YAML 파일을 Open
4. 이곳에서 복사하거나 받은 파일을 사용하고
5. Build 하게 되면 바로 적용됩니다.
6. sbml, sbss, bon 파일 열림 프로그램 설정은 알아서 파일연결(파일 정보보기에서 설정)

## 참고링크 
* https://packagecontrol.io/installation#st2
* http://sublimetext.info/docs/en/extensibility/syntaxdefs.html
* http://sublime-text-unofficial-documentation.readthedocs.org/en/latest/extensibility/syntaxdefs.html
