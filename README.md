## This-is-a-two-day-challenge.

#### 1. 현재 진행중인 곡의 control box(첫 번째 스크린 하단의 검정색 box)
position: absolute로 구현할 수 있습니다. </br>
absolute로 지정한 element를 가운데 정렬하는 방법은 다양합니다. </br>
예시에선 left: 0; right: 0; margin-left: auto; margin-right: auto; width: (특정 값); 으로 구현했습니다. </br>
이전 챌린지 중에 언급했던 transform: translate(..)로도 구현할 수 있습니다. </br>
left: 0; transform: translateX(-50%); </br>

#### 2. 진행 bar(두 번째 스크린 하단 부분)
답안에서의 구현한 방법은 이미 재생된 부분, 현재 재생 위치, 전체 재생 길이 를 형제관계로 나열하고, 이미 재생된 부분과 현재 재생 위치에 absolute를 적용해 구현했습니다. </br>
absolute는 해당 요소를 문서의 흐름에서 벗어나게 합니다. 만약 absolute를 사용하지 않았다면 세 부분은 위에서 아래로 나열되었을 것입니다. </br>
답안의 방법 말고도 전체 재생 길이 의 자식으로 이미 재생된 부분과 현재 재생 위치이 있는 구조로 구현해도 됩니다. </br>
![ex01](https://user-images.githubusercontent.com/88027485/196057396-d526b3a9-93c1-42e7-a220-1d06b54a4d2a.png) </br>
오히려 이쪽이 직관적이며, 코드 작성이 더 쉬울 수 있습니다.

#### 3. opacity
opacity로도 회색을 표현할 수 있습니다. </br>
opacity는 불투명도를 조절하는 속성으로, text 뿐만 아니라 image를 비롯한 모든 요소에 적용할 수 있습니다.
