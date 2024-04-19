[![English](https://img.shields.io/badge/lang-English-blue.svg)](https://github.com/juho-creator/VirtualWorlds/blob/main/README.md)


# 가상세계
이 리포지토리는 이강훈 교수님의 가상세계 과제입니다.

</br></br>



# 시연영상
[![maxresdefault](https://github.com/juho-creator/VirtualWorlds/assets/72856990/3064f332-286b-4337-b3cf-82939a44bf74)
](https://www.youtube.com/watch?v=jLfZWK6fyUM)
</br></br>

## 프로젝트 진행도
![image](https://github.com/juho-creator/VirtualWorlds/assets/72856990/c738694b-9505-43f3-ad22-033e68729204)
</br></br>

## 프로젝트의 한계
현재 프로젝트는 아래와 같은 한계를 지니고 있습니다 : 
1. 다가오는 차량이 곡선 도로에서 유턴을 할 수 없음
2. 곡선 도로에서 유턴할때 카메라가 플레이어 자동차를 따라가지지만 회전하지 않음
</br></br>


## 한계 극복을 위한 시도

> [!NOTE]
> **과제 평가 과정에서 혼란을 방지하기 위해 오작동하는 코드는 삭제했습니다.**
</br>

- **곡선 도로에서의 차량 이동 가능하게 하기**  
  곡선 도로에서 차량이 드리프트할 수 있도록 수많은 시도를 해봤습니다. 결국 여러번의 시행착오를 통해 차량이 곡선 도로에서 수평이동하도록 구현해봤습니다:

https://github.com/juho-creator/VirtualWorlds/assets/72856990/ba0d4062-43ab-466e-ae2f-ab77efc327a9


하지만 차량은 곡선 도록에 진입할 때가 아니라 곡선 도록의 가장자리에서만 드리프트하기 시작했습니다. </br>

  
- **차량으로부터 카메라 거리 유지하기**  
  차량으로부터 일정 거리를 유지하도록 카메라를 프로그래밍하여 자동차의 시점을 유지했습니다. </br>
직선 도로에서는 차량의 시점을 적절히 유지하는듯 보여줬지만, </br>
곡선 도로에서는 차량을 따라 적절하게 회전할 수 없었습니다.
</br></br>


## 사용된 개념
- 삼각함수
- 메쉬와 쿼드
</br></br>


# 참고문헌
- [Procedural Mesh tutorial](https://www.youtube.com/watch?v=ucuOVL7c5Hw&list=PL5KbKbJ6Gf9-d303Lk8TGKCW-t5JsBdtB)
- [Application of Bezier curve](https://www.youtube.com/watch?v=BQvBq3K50u8)
- [2D Curve Introduction and Concepts](https://www.youtube.com/watch?v=RF04Fi9OCPc&list=PLsCt1Wdr6utD1wqJ1GB_cFjhgtUXO-osI)
