# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 양기택
- 리뷰어 : 진수민


# PRT(Peer Review Template)
- [△]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 1. 전처리 : 텍스트 길이 확인 및 정규화 사전을 통해 확인, 불용어개수 파악 등 순서대로 잘 진행되었음
             ![image](https://github.com/user-attachments/assets/88667c2a-f9a6-40a4-bf2e-8f4fc2bc9577)
             ![image](https://github.com/user-attachments/assets/53808ab3-5087-4a10-bf4f-49b0127f97d6)
        - 2. 모델 학습 후 loss 그래프를 작성함
             ![image](https://github.com/user-attachments/assets/2f6df7b9-a8d8-4ce8-a63d-83b9a811d270)
        - 3. 추출 추상 요약 결과 비교를 시간관계상 진행하지 못했다고 함.


    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        ![image](https://github.com/user-attachments/assets/b4400bf3-5ab0-40e8-96e1-6c288b4662c6)

    

        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - padding을 pre로 작성하여 실험해봄
        - ![image](https://github.com/user-attachments/assets/64f7cf09-9226-48b3-adff-c784d26bef52)
        - 정규 표현식 부분을 바꾸어 작성함
        - ![image](https://github.com/user-attachments/assets/61bcd1bd-0c0b-4681-b1d0-c2cfd0a04fe4)



        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 학습노드의 핵심적인 부분 lstm과 어텐션 모델의 활용에 대해서 파악함
        - ![image](https://github.com/user-attachments/assets/56312f4b-b3ba-4326-88b8-0a709b73cf57)

        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 코드 가독성을 높이고자 정규 표현식을 수정함
        - ![image](https://github.com/user-attachments/assets/3c2dc377-acd0-433c-bbcd-aed4adffdb29)



# 회고(참고 링크 및 코드 개선)
```
- 코드에 대한 설명을 상세하게 기술하셔서 읽는데 수월했습니다!
- 실험을 시간 내에 완성하지 못한 점이 아쉬움이 남습니다.
```
