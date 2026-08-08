[GitHub README.md](https://github.com/user-attachments/files/30849346/GitHub.README.md)
<img width="1278" height="702" alt="캡처" src="https://github.com/user-attachments/assets/3461b615-3cd1-4fc3-ab9d-0ec5f9d2cd36" />

<img width="1197" height="785" alt="캡처2" src="https://github.com/user-attachments/assets/bad036b2-4ec3-4552-916e-40a4df640e77" />

<img width="1099" height="620" alt="캡처3" src="https://github.com/user-attachments/assets/49e65eea-ade7-4401-b40d-bfc10fba0f91" />

<img width="1101" height="510" alt="캡처4" src="https://github.com/user-attachments/assets/da4393ae-6d65-4bdb-9a45-5dc085879a8b" />

# **3D 미로 탈출 게임 (3D Maze Escape Game) 🕹️**

**Three.js**와 **HTML5**로 완전히 제작된 1인칭 3D 미로 탈출 게임입니다. 어둡고 복잡한 미로 속에서 손전등을 활용해 길을 찾고, 황금 블록을 찾아 다음 단계로 나아가세요\!

## **🌟 주요 기능 (Features)**

* **1인칭 시점:** PointerLockControls를 적용하여 부드러운 FPS 스타일의 마우스 시점 전환과 키보드 이동을 지원합니다.  
* **다이나믹 손전등 효과:** 스포트라이트 조명 효과를 제공합니다.  
* **어두운 배경:** 배경을 어둡게 하여 긴장감을 주고 약간의 공포요소를 더합니다.  
* **다양한 레벨:** 점진적으로 난이도가 높아지는 3단계로 이루어진 복잡한 미로 게임을 제공합니다.  
* **제로 디펜던시 설정:** 별도의 복잡한 번들러나 설치 과정 없이 CDN 기반의 Three.js를 활용하여 단일 HTML 파일로 실행됩니다\!

## **🎮 게임 플레이 방법 (How to Play)**

1. **게임 시작:** 웹 브라우저에서 게임을 열고 화면을 클릭하면 마우스 포인터가 잠기며 게임이 시작됩니다.  
2. **조작법 (Controls):**  
   * **이동:** W(앞), A(왼쪽), S(오른쪽), D(뒤) 키  
   * **시점 조절:** 마우스 이동  
   * **탈출 방법:** 미로 어딘가에 숨겨진 황금 블록(G)을 찾아 총 3개의 스테이지를 클리어하세요.  
3. **마우스 해제:** 마우스 커서를 해제하고 싶을 때는 ESC 키를 누르세요.

## **🛠️ 기술 스택 (Tech Stack)**

* **HTML5 & CSS3** (UI 오버레이 및 스타일링)  
* **JavaScript (ES6+)** (게임 로직 및 물리 시뮬레이션)  
* **Three.js (r128)** (3D 그래픽 렌더링, 머티리얼 및 조명)

## **🚀 로컬 실행 방법 (Quick Start / Running Locally)**

이 프로젝트는 단일 파일로 구성된 웹 애플리케이션이므로 로컬에서 매우 간단하게 실행할 수 있습니다:

1. 이 저장소를 클론하거나 다운로드합니다.  
2. 코드를 index.html 파일로 저장합니다.  
3. 웹 브라우저(Chrome, Firefox, Edge, Safari 등)에서 index.html을 직접 엽니다.

*(참고: 추후 텍스처나 에셋을 확장할 때 로컬 CORS 제한을 피하려면, VS Code의 **Live Server** 같은 로컬 개발 서버를 사용하는 것을 권장합니다.)*

