# Starbucks Scraping Prompt

1) HTTP 요청정보와 헤더
Request URL
https://www.starbucks.co.kr/store/getStore.do?r=5ALMDL102B
Request Method
POST
Status Code
200 OK
Remote Address
182.173.169.11:443
Referrer Policy
strict-origin-when-cross-origin

host
www.starbucks.co.kr
origin
https://www.starbucks.co.kr
referer
https://www.starbucks.co.kr/store/store_map.do
sec-ch-ua
"Google Chrome";v="147", "Not.A/Brand";v="8", "Chromium";v="147"
sec-ch-ua-mobile
?0
sec-ch-ua-platform
"macOS"
sec-fetch-dest
empty
sec-fetch-mode
cors
sec-fetch-site
same-origin
user-agent
Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/147.0.0.0 Safari/537.36


2) Payload 정보
in_biz_cds=0&in_scodes=0&ins_lat=37.56682&ins_lng=126.97865&search_text=&p_sido_cd=01&p_gugun_cd=&isError=true&in_distance=0&in_biz_cd=&iend=1000&searchType=C&set_date=&rndCod=51APT9YK7R&all_store=0&T03=0&T01=0&T27=0&T12=0&T09=0&T30=0&T05=0&T22=0&T21=0&T36=0&T43=0&Z9999=0&T64=0&P02=0&P10=0&P50=0&P20=0&P60=0&P30=0&P70=0&P40=0&P80=0&whcroad_yn=0&P90=0&P01=0&new_bool=0

3) 응답의 일부를 Response 에서 일부를 복사해서 넣어주기 (전체는 토큰 수 제한으로 어렵습니다.)
list 하위의 모든 정보 수집
```
{
    "list": [
        {
```

4) 한페이지가 성공적으로 수집되는지 확인하기​