## request
```python
import request
```
Python에서 HTTP 요청을 보내기 위해 가장 널리 쓰이는 라이브러리이다.
requests는 모듈 전체를 의미하며, 그 안에 핵심적인 역할을 하는 Response 클래스와 Session 클래스 등이 포함되어 있다.  
<br/> 

### 주요 메서드
* requests.get(url): 데이터 조회
* requests.post(url, data=...): 데이터 생성/전송
* requests.put(url, data=...): 데이터 수정
* requests.delete(url): 데이터 삭제
<br />

### 핵심 클래스: Response 객체
requests.get() 등을 호출하면 반환되는 결과물이 바로
**Response** 클래스의 인스턴스이다. 이 객체에 서버가 보낸 모든 정보가 담겨 있다.    
> <img width="650" height="260" alt="image" src="https://github.com/user-attachments/assets/ba945d15-408a-41fc-ae62-dff3c458400a" />  
> <img width="566" height="263" alt="image" src="https://github.com/user-attachments/assets/3955b98c-69d8-4df7-a975-6257badb0ccd" />
> <img width="558" height="261" alt="image" src="https://github.com/user-attachments/assets/e59ef384-fafc-44d4-9598-9526c27b9566" />
> <img width="633" height="223" alt="image" src="https://github.com/user-attachments/assets/a7ef2abd-ad25-4cb1-a646-bc2011516e0b" />








