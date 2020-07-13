KaKaotalk Bot 
=============
본 코드는 Violet XF 님의 Messenger bot에서 동작하는 코드. 

목적
====
주식 거래시 MTS와 카카오톡을 왔다갔다 하며 정보를 얻는것이 불편한 것에서 착안  
자동응답 기능을 이용하여 카카오톡 에서도 실시간으로 정보를 얻어오기 위함.

기능
===  
    /확률 [A]  
A할 확률 출력  

    /vs [A] [B]  
A 와 B 둘중 하나 랜덤 선택  

    /주가 [종목명]  
요청 시간의 종목의 주가를 알림  

    /종목등록,추가,삽입 [종목] [단가=0] [수량=0]
DB처럼 동작하며 사용자의 관심종목을 추가  

    /종목초기화
해당 사용자의 종목 초기화  

    /종목보기,조회,확인  
해당 사용자의 종목 확인

    /자산평가  
사용자의 관심종목의 등락을 계산, 손익을 출력  

    /종목삭제 [종목]  
입력한 종목을 사용자 관심종목에서 삭제  

    /알림등록,추가,삽입 [종목] 고점[n] 저점[n]  
해당 종목에 대한 고점과 저점을 설정하며, 알람온 으로 알림  

    /알림온 [n분]  
n분간 해당 주가의 설정 가격 도달시 알람 기능 ON  

    /알림초기화  
    /알림보기,조회,확인  
    /알림삭제  [종목]  
위와 동일

    /부동산검색 [주소]  
    /게시판업데이트  
미구현 기능

    

etc
===
[API리스트](https://deviolet.tistory.com/entry/메신저봇-가이드-레거시-API "go to Dev Blog")
