# clipboard_tranlater
 파파고 api를 활용한 반투명 클립보드 번역 앱

## 사용 방법

https://developers.naver.com/docs/papago/papago-nmt-api-reference.md

위 API 레퍼런스 설명과 같이 클라이언트 아이디와 클라이언트 시크릿을 발급 받아서 다음 변수에 추가 해야합니다.

```python
self.papago_id = "클라이언트 아이디"
self.papago_secret = "클라이언트 시크릿"
```

![](https://github.com/iknoom/clipboard_tranlater/blob/master/image/translate_example.PNG)

실행 후 번역할 문장을 [Ctrl + C]로 복사하면 번역 앱에 번역됩니다.

왼쪽 slider : 투명도

오른쪽 slider : 폰트 크기

우클릭 매뉴 : 앱 종료, 언어 변경(일본어)
