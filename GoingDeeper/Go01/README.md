# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김지환
- 리뷰어 : 김성훈

# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**

    - ![image](https://github.com/user-attachments/assets/ed03d4bd-66a1-4d9b-bdf9-d02521cd4362)

    - ![image](https://github.com/user-attachments/assets/d4d58973-72c6-41bd-a213-e02e3ae57d71)

    - ![image](https://github.com/user-attachments/assets/fe061359-f305-42de-84ca-a2e3bd665b3b)

    - ![image](https://github.com/user-attachments/assets/e8a7733f-685b-4c2c-9eac-feae15572fc9)

    - ![image](https://github.com/user-attachments/assets/aaa45489-d219-444a-9c00-ac017038e345)


- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    
    - ![image](https://github.com/user-attachments/assets/52ea7802-15e9-4140-a020-952cea856143)
    - 각기 다른 구조의 모델을 학습하고 바로 이어서 결과를 분석하는 것까지 한 번에 처리하여 실험 편의성을 높였다.
    - 코드 블럭 내 주석을 통해 각 코드의 기능, 존재 이유 등을 기술하였다.

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
  
    - CIFAR10 데이터셋에서 먼저 실험을 진행 후 추가로 Cats vs Dogs 데이터셋에서 실험을 진행하였다.

        
- [x]  **4. 회고를 잘 작성했나요?**
      
    - 프로젝트 진행하며 배운점과 아쉬운점, 느낀점 등이 명료하게 기록되어 있다.

        
- [ ]  **5. 코드가 간결하고 효율적인가요?**



# 회고(참고 링크 및 코드 개선)
```
논문에 등장한 잔차 연결 구조(Post-activation)를 시도해본 점이 인상 깊습니다. 해당 프로젝트를 하며 개인 학습에 도움이 되는 부분을 최대한 챙기려고 한 고민의 흔적이 보입니다.
학습과 결과 시각화까지 이어서 진행되도록 하여 실험 편의성이 높인 부분이 좋았습니다. 그러나 각각을 함수로 만들었으나 이후 추가 실험에서 사용하지 않고 다시 코드를 반복한 부분은 아쉽습니다.
최적 적합의 모델 완성보다는 각 모델 구조의 학습 과정을 관찰하는 것이 더 중요했다고 생각합니다. 이 점을 감안할 때 Early Stopping 적용 없이 동일한 epoch를 진행했다면 더 좋을 것 같습니다.
프로젝트를 진행하는 방식이 남달라서 시야가 더 넓어진 느낌입니다. 덕분에 좋은 공부가 되었습니다.
```
