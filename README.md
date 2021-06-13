# Capston AD1 Result

본 저장소는 경상대학교 정보통신공학과 캡스톤디자인 AD-1팀의 결과 보고 저장소 입니다. 

팀원: [최윤도(팀장)](https://github.com/zygn), [김강진](https://github.com/nurdy-kim), [김준수](https://github.com/junsu-kim-creator), [김두현](https://github.com/durian977), [이정민](https://github.com/LJM0207)


---

## 1. 요구사항 
### 1.1. Use Case Model
 - [Capston Design - 요구사항 분석](https://github.com/zygn/Capston_AD1_Result/blob/main/1.%20%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD/Capston%20Design%20-%20%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%20%EB%B6%84%EC%84%9D.pdf)

## 2. 구현 결과

### 2.1 ROS Environment with JIT Compiler
![]('https://github.com/zygn/Capston_AD1_Result/blob/img/img/ros.tiff')
![]('https://raw.githubusercontent.com/zygn/Capston_AD1_Result/img/img/ros-vscode.png')
### 2.2 A* Path Planning
![]('https://raw.githubusercontent.com/zygn/Capston_AD1_Result/img/img/astar.png')
### 2.3 Obstacle Avoidance with DQN
![]('obstacle_dqn.png')
 - [Capston Design - 구현 결과]()



## 3. 기타

### 의존성
- 프로젝트에 사용된 프로그램 및 의존성 패키지는 다음과 같습니다. 

    Python 3.8.x (build from Anaconda)
    - numpy 
    - numba 
    - gym
    - tensorflow
    - keras
    - yaml
    - logging
    - rospy

    Planner
    - PurePursuitPlanner
    - AStarPlanner

    ROS Melodic (Car System)
    - Python 2.7.x
    - Python 3.8.x (build from Anaconda)


### 환경

 - 강화학습을 위한 시뮬레이션 환경은 [f1tenth/f1tenth_gym](https://github.com/f1tenth/f1tenth_gym) 을 사용하였습니다. 

### 프로젝트 저장소

 - [zygn/Capston_AD1](https://github.com/zygn/Capston_AD1) 에서 확인 하실수 있습니다. 

### 발표 자료
 - [Capston Design - 발표 자료]()

