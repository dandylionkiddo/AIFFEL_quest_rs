# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김지환
- 리뷰어 : 조성호


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 네
    - 코드의 마지막에 한국어 대화가 가능함을 보였다.

![image](https://github.com/user-attachments/assets/f9050cfe-0c12-43c8-bfee-06b3f85b5a50)

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 네
    - 모델에 early stopping, 학습률 감소 콜백 추가한 부분에 주석이 이해를 도왔다.
     
<img width="737" alt="image" src="https://github.com/user-attachments/assets/ee2bde0b-08ef-43e7-a704-6a996ed6b7c4" />

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 네
    - 모델에서 아래와 같은 부분은 수정하며 많은 학습을 진행하였다.
        - 인코더와 디코더의 층 개수
        - 인코더와 디코더 내부의 입출력 고정 차원
        - 에포크 수 늘리기
        - dropout 비율 변경
        - weight decay 추가
        - early stopping 적용
        - 형태소 분석기 사용
     
![image](https://github.com/user-attachments/assets/540df620-6e18-4610-9fa4-0196be214993)

![image](https://github.com/user-attachments/assets/9c9f43b3-ce0b-4afa-986f-2ad23c83ce05)

        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 네
    - 실험 결과가 좋았던 부분과 개선사항을 작성했다.

![image](https://github.com/user-attachments/assets/6d0d367b-ae32-4c83-b126-ae45f61b5900)

        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 아니오
    - 모델의 많은 부분을 건드렸고, 그때마다 코드를 다시 작성하여 간결하다는 느낌은 받지 못했다.
    - 시간이 조금 더 있었다면 모델을 수정할 때 필요한 부분만 바꿀 수 있도록 함수화하면 더 좋을 것 같다.


# 회고(참고 링크 및 코드 개선)
```
저는 사용하지 못한 콜백 함수나 형태소 토크나이저를 확인할 수 있어 의미있는 시간이였습니다.
지환 님께서 사용하신 모델 변경사항을 제 코드에 적용하면 어떤 결과가 나올지 궁금했습니다.
```
