# Algorithms for Optimization

- 경기대학교 최현집 교수님의 2020년도 2학기 "최적화 방법 및 실습" 강의 정리
    - Algorithms for Optimization (Mykel J.Kochenderfer and Tim A.Wheeler) 교재 기반

- 최적화에 관한 기초적인 내용
    - 나름 열심히 들었지만 어려웠다.
    - 피상적으로만 이해해서 나중에 더 깊게 이해할 필요 있음.

## 수업에서 느낀 점

- hyper parameter의 중요성 파악할 수 있었다.
    - 2019년도 겨울방학때 참여한 kaggle "Boston 집값 예측"프로젝트에서, RMSE 수치를 낮추기 위해 하이퍼 파라미터만 밤새도록 조정해 팀원 중에서 가장 낮은 RMSE 경험했다.
    - 통계 기초과목인 회귀분석도 배우지 않아서 RMSE라는 개념도 모르고, 아는게 거의 없는 비전공자 상태였다.
    - 관련 프로젝트가 끝난후, 다른 조의 결과물을 들으면서 grid-search를 이용해서 최적의 하이퍼 파라미터를 찾는 방법이 존재한다는 것을 알고나서 비효율적인 일을 했다고 생각했다.
    - 나는 밤 새 하이퍼 파라미터만 조정했는데 다른 조들은 grid-search 관련 코드를 구현함으로써 가장 나은 결과를 도출하는 하이퍼 파라미터를 찾았고 모델링에 더 신경을 써서 우리 조 보다 훨씬 더 나은 결과물을 도출했고, 지구의 곡면까지 계산을 하는 모형을 설계했다. (나중에 알았지만 상위 커널을 보고 따라했다고 한다. 나는 이 때 상위 커널을 보는 법을 아예 몰랐고 그런게 있는 줄도 몰랐다.)
    - 하지만 이 수업을 통해 직접 hyper parameter를 조정하며 모형이 어떻게 바뀌는지 파악했던 경험이 절대 헛된 경험이 아니라는 것을 알게 되었다.
    
- 코드 한 줄에는 생각보다 많은 이론적 배경이 있다는 것을 배웠다.
    - 20년도 1학기 대외활동에서 딥러닝 기초 개념을 배우고 코드를 구현했는데, tf.keras.optimizers.Adam 이라는 코드를 통해 Adam최적화를 수행했다.
    - 하지만 이 강의를 들으며 Adam이 나오기까지의 과정과 구체적인 수식 등을 배우며 한 줄짜리 간단한 코드로 구현된다고 해서 관련 이론 공부도 소홀히 하면 안된다는 것을 느꼈다.
    - 패키지를 사용해서 코드를 구현하기만 하는 것이 아니라, 코드가 무엇을 하는지 정확하게 이해하고 코딩을 하는 것이 중요하다는 것을 느꼈다.
        - "이해"를 기반으로 코드를 "구현"하자~
 
- 최적화는 어렵다~!
    

## 목차
1. Introduction
2. Derivate, Gradient
3. Bracketing
4. Bracketing
5. Local Descent
6. Local Descent
7. Code with sympy library
8. First-Order Methods
9. Gradient Descent
10. Gradient Descent
11. Second-Order Methods
12. Stochastic Methods
13. Genetic Algorithm
14. Surrogate Models

