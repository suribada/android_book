# 안드로이드 프로그래밍 Next Step : 제대로 된 앱을 만드는 컴포넌트 활용 노하우

## 예제 소스
https://github.com/suribada/androidBookSample
## 기초 원고
latexbook 아래 위치. 편집 검토하면서 내용이 많이 변경

# 정오표
- 3p. 10라인 씬 클라인언트->씬 클라이언트
- 49p. 2라인 스레드가 스레드를 -> 스레드 풀에서 스레드를
- 54p. 15, 16라인 DelayWorkQueue -> DelayedWorkQueue(제보해주신 loadofnightmare.9876님 감사합니다.)
- 56p. 4라인 setCorePoolSiz() -> setCorePoolSize()(제보해주신 황두영님 감사합니다.)
- 73p. 1라인 ContetImpl -> ContextImpl(제보해주신 김동진님 감사합니다.)
- 73p. 3라인 Context Wrapper -> ContextWrapper
- 86p. 코드 5-2 3라인 ActvityA -> ActivityA
- 86p. 코드 5-2 6라인 제거 필요(제보해주신 loadofnightmare.9876님 감사합니다.)
- 126p. SplashPage와 SplashActivity가 혼용되어 있음. SplashActivity로 맞춤
- 233p. 11라인 불필요하도록 오버라이드한 -> 불필요하도록 오버로드한
- 228p 코드 9-3 (1) 비교 로직 if (each.pid == android.os.Process.myPid() && each.processName.equals(getPackageName()) {

# 의미 정정
교정 및 편집으로 문장을 맞추다가 뉘앙스가 변경된 경우
- 94p 아래 6라인: 떠 있는 Activity에 특별한 작업을 하기 위해서 Activity 인스턴스를 컬렉션(Colletion)에 모아둔다. 최악의 상황으로 ~
 -> 떠 있는 Activity에 특별한 작업을 하기 위해서 Activity 인스턴스를 컬렉션(Colletion)에 모아두기도 한다. 이는 그다지 좋지 않은 상황이다.(제보해주신 정기용님 감사합니다.)

## 판매 위치
- Yes24: http://www.yes24.com/24/goods/41085242
- 알라딘: http://www.aladin.co.kr/shop/wproduct.aspx?ItemId=110015332
- 인터파크: http://book.interpark.com/product/BookDisplay.do?_method=detail&sc.shopNo=0000400000&sc.prdNo=267623437&sc.saNo=003002001&bid1=search&bid2=product&bid3=title&bid4=001
- 교보문고: http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788966263073&orderClick=LET&Kc=

# 기타
- 문의는 Issues에 올려주세요.

