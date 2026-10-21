# 이동준 Dongjun Lee

### AI Vision & Robot Software Developer

AI 비전의 인식 결과가 실제 로봇 동작으로 이어지도록 연결합니다.  
로그와 실패 장면을 바탕으로 원인을 나누고, 같은 입력에서 수정 전후를 확인합니다.

[포트폴리오](https://omveryo.github.io/) · [Notion 상세 기록](https://app.notion.com/p/5e18a6d7140b8345ade101b81971344b) · [Email](mailto:omver5669@gmail.com)

## About

- **관심 분야**: AI 비전, ROS2 로봇 소프트웨어, AMR 주행 및 시스템 통합
- **인턴**: 미디어그룹 사람과숲, 2023.10–2024.01 — MediaPipe 동작 비교와 Flask·SQLAlchemy·MySQL·Unreal 클라이언트 연동
- **학력**: Auckland University of Technology, Software Development, 2021.11 졸업
- **교육**: 두산로보틱스 로키 부트캠프 9기, 2026.04–2026.10 — 협동로봇·AMR 팀 프로젝트 5건
- **영어**: OPIc AL (Advanced Low), 2026.02

## Selected projects

| 프로젝트 | 제가 맡은 일 | 사용 기술 |
| --- | --- | --- |
| [SCV 물류창고 자율점검](https://github.com/OmverYo/B_0102_Final_Project) | YOLO 학습·검출 테스트, 설비별 후처리, ROS2 검사 연동 | Python, OpenCV, YOLO, RGB-D, ROS2 |
| [도서 자동 배가](https://github.com/OmverYo/book-shelving-system) | 지도·Nav2 구성, 경유점 주행, 작업 위치 정렬·복귀 | Python, ROS2, Nav2, Isaac Sim |
| [음성·손동작 장기말 로봇](https://github.com/OmverYo/drb3_ai) | YOLO 모델 비교, 웹·Flask·MongoDB 연결, 프롬프트·Git 관리 | YOLO, Flask, MongoDB, Socket.IO |
| [RC카 추종 AMR](https://github.com/OmverYo/b-1_mini_project) | 언독·초기 위치, Nav2 준비 확인·복구, 이동·탐색·복귀·도킹 | Python, ROS2, Nav2, TurtleBot4 |
| [DOT.ON 한글·점자 카드](https://github.com/OmverYo/drb3) | 캘리그라피·점자 실행 코드, 로봇 환경, 일정·Git 협업 | Python, ROS2, Doosan M0609 |

팀 프로젝트의 전체 구현과 본인 기여 범위를 구분했습니다. 문제 해결 과정과 검증 범위는 [메인 포트폴리오](https://omveryo.github.io/#projects)에서 확인할 수 있습니다.

## How I work

**입력과 실행 조건을 구분합니다.** 인식이 맞는지, 데이터가 전달되는지, 로봇이 준비됐는지 순서대로 살핍니다.

**수정 전후를 비교합니다.** SCV의 한 녹화 75프레임 비교에서 벽 오검출은 74→0프레임으로 줄이고 실제 상자 검출은 75/75를 유지했습니다. 제한된 녹화 시험의 결과이며 일반 성능 수치로 확대하지 않습니다.

**다음 모듈까지 연결합니다.** 인식·서버·DB·웹과 로봇 주행을 각각의 기능에서 전체 작업 흐름으로 연결하는 데 관심이 있습니다.

## Tools I have used

- **Vision**: OpenCV, YOLO, MediaPipe, NumPy, RGB-D post-processing
- **Robotics**: ROS2, rclpy, Nav2, Isaac Sim, RViz2
- **Integration**: Python, Flask, REST API, SQLAlchemy, MySQL, MongoDB, Socket.IO
- **Environment**: Ubuntu/Linux, Git, GitHub, Notion
- **Foundational learning**: C/C++, PyTorch, TensorFlow

## In English

I connect computer vision outputs to robot actions. My experience includes a motion-analysis internship and five collaborative robot and AMR team projects. I focus on input data, module interfaces and robot readiness, using failure cases and repeatable comparisons to guide improvements.

[Explore my portfolio in English](https://omveryo.github.io/?lang=en)
