# Algorithms for Optimization

- 경기대학교 최현집 교수님의 2020년도 2학기 "최적화 방법 및 실습" 강의 정리
    - Algorithms for Optimization (Mykel J.Kochenderfer and Tim A.Wheeler) 교재 기반

- 최적화에 관한 기초적인 내용
    - 피상적으로만 이해해서 나중에 더 깊게 이해할 필요 있음.

## 수업에서 느낀 점

- hyper parameter의 중요성 파악할 수 있었다.
    - 2019년도 겨울방학때 참여한 kaggle "Boston 집값 예측"프로젝트에서, RMSE 수치를 낮추기 위해 하이퍼 파라미터만 밤새도록 조정해 팀원 중에서 가장 낮은 RMSE 경험했다.
    - 통계 기초과목인 회귀분석도 배우지 않아서 RMSE라는 개념도 모르고, 아는게 거의 없는 비전공자 상태였다.
    - 관련 프로젝트가 끝난후, grid-search를 이용해서 최적의 하이퍼 파라미터를 찾는 방법이 존재한다는 것을 알고나서 비효율적인 일을 했다고 생각했다.
    - 하지만 이 수업을 통해 직접 hyper parameter를 조정하며 모형이 어떻게 바뀌는지 파악했던 경험이 절대 헛된 경험이 아니라는 것을 알게 되었다.
    
- 코드 한 줄에는 생각보다 많은 이론적 배경이 있다는 것을 배웠다.
    - 20년도 1학기 대외활동에서 딥러닝 기초 개념을 배우고 코드를 구현했는데, tf.keras.optimizers.Adam 이라는 코드를 통해 Adam최적화를 수행했다.
    - 하지만 이 강의를 들으며 Adam이 나오기까지의 과정과 구체적인 수식 등을 배우며 한 줄짜리 간단한 코드로 구현된다고 해서 관련 이론 공부도 소홀히 하면 안된다는 것을 느꼈다.
    - 패키지를 사용해서 코드를 구현하기만 하는 것이 아니라, 코드가 무엇을 하는지 정확하게 이해하고 코딩을 하는 것이 중요하다는 것을 느꼈다.
        - "이해"를 기반으로 코드를 "구현"하자~
 
- 최적화는 어렵다~!
    

## 목차
1. Introduction
2. 도함수(Derivate), 경사도(Gradient)
3. 구간분할법 (Bracketing)
4. 구간 분할법과 경사법(Local Descent)
5. 경사법
6. 경사법2
7. sympy 라이브러리를 활용한 실습
8. 일차 미분 이용한 방법들
9. 경사하강법 (Gradient Descent) 
10. 경사하강법2 (Gradient Descent) 
11. 이차미분 근사법
12. 확률적인 방법들 (Stochastic Methods)
13. 유전자 알고리즘 (Genetic Algorithm)
14. Surrogate Models

