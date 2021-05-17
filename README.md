# ediya-coffee

https://bullkhan.github.io/idiya-coffee/


CORS 정책으로 인한 블락 현상을 일시적 해결을 위해
미세먼지 API 허용을 위해 빈사이트에
https://cors-anywhere.herokuapp.com/http://apis.data.go.kr/B552584/ArpltnInforInqireSvc/getCtprvnRltmMesureDnsty?sidoName=${sidoname}&pageNo=1&numOfRows=1&returnType=json&serviceKey=BlwPga%2Bo1YICKpfxUbl7QML5sbuVc%2Bu5Mk%2FsUUJ8m7CqbJoEcjPVminKhtHsh%2F1sSakVAa6Vhqo4s38iIh%2FcIA%3D%3D&ver=1.0
열어서 임시 CORS 허용해야 함.


임시 CORS 허용을 클라이언트 쪽에서 주소 이동 후 허용버튼 클릭하게 하는 문제 해결함.
허용 요청시 자동 처리하게끔 함.
