# my-3d-room
# 🏡 3D Vibe Room Simulator

[![GitHub Pages 배포 상태](https://img.shields.io/github/deployments/haheehee/my-3d-room/github-pages?label=GitHub%20Pages&logo=github)](https://haheehee.github.io/my-3d-room/)

**3D Vibe Room Simulator**는 웹 브라우저 기반의 간단한 3차원 공간 설계 도구입니다. 복잡한 설치 없이 바로 방의 크기를 설정하고, 가구, 문/창문을 배치하여 나만의 공간 레이아웃을 빠르게 시각화할 수 있습니다.

## ✨ 주요 기능

* **📏 방 커스터마이징:** 가로, 세로, 깊이를 직접 입력하여 원하는 크기의 방을 생성합니다.
* **🛋️ 드래그 & 드롭 배치:** 방 안에 가구를 배치하고 마우스 조작으로 쉽게 이동시킬 수 있습니다.
* **🚪 문/창문 구현:** 벽면에 문이나 창문 오브젝트를 배치하고 스윙 방향을 설정할 수 있습니다.
* **⚙️ 통합 속성 수정:** 객체(방, 가구, 문)를 **더블 클릭**하여 모든 속성을 하나의 팝업창에서 한 번에 수정할 수 있습니다.
* **💾 저장 및 불러오기:** 현재 레이아웃을 파일로 저장하고 언제든 다시 불러와 작업을 이어갈 수 있습니다.

---

## 🚀 사용 방법

### A. 방 만들기 및 가구 배치

1.  **🏠 새 방 만들기:**
    * 좌측 패널에서 **'방 크기 설정'** 섹션의 `가로(W)`, `세로(H)`, `깊이(D)` 값을 미터 단위로 입력합니다.
    * `🏠 새 방 만들기` 버튼을 클릭합니다.
    
2.  **🛋️ 가구 배치하기:**
    * 좌측 패널 **'가구 추가'** 섹션에서 배치할 방을 선택합니다.
    * 가구의 `가로(W)`, `세로(H)`, `깊이(D)`와 색상을 설정합니다.
    * `가구 배치하기 (+)` 버튼을 클릭하면 방 중앙에 가구가 배치됩니다.
    
3.  **🚪 문/창문 배치:**
    * 좌측 패널 **'문/창문 배치'** 섹션에서 배치할 방을 선택합니다.
    * 문 너비(W), 배치할 벽면, 경첩/스윙 방식(예: `L_IN` 등)을 선택합니다.
    * `🚪 문 배치하기 (+)` 버튼을 클릭합니다.

### B. 객체 조작 및 수정

| 액션 | 대상 | 설명 |
| :--- | :--- | :--- |
| **더블 클릭** | 방, 가구, 문 | **통합 속성 수정 모달**을 열어 크기, 색상, 스윙 타입 등을 한 번에 수정합니다. |
| **마우스 드래그** | (빈 공간) | 3D 시점(카메라)을 회전시킵니다. |
| **Shift + 드래그** | 가구, 문 | **수평면**에서 객체를 이동시킵니다. |
| **Ctrl + 드래그** | 가구 | **수직 방향**으로 객체를 이동시킵니다. |
| **Alt + Shift + 드래그** | 방 | 방 전체를 수평면에서 이동시킵니다. |

---

## 🛠️ 개발 환경

이 프로젝트는 별도의 서버 측 스크립트 없이 오직 클라이언트 측 기술만으로 구현되었습니다.

* **HTML5 / CSS / JavaScript:** 기본 구조 및 로직
* **Three.js (r128):** 3D 렌더링 엔진
* **OrbitControls:** 마우스 기반 3D 시점 제어

---

## 🔗 프로젝트 링크

| 구분 | 주소 |
| :--- | :--- |
| **라이브 데모** | **[여기를 클릭하여 시뮬레이터 실행]**(https://haheehee.github.io/my-3d-room/) |
| **GitHub 리포지토리** | [https://github.com/haheehee/my-3d-room/](https://github.com/haheehee/my-3d-room/) |


---

## 📄 라이선스

MIT License

# my-3d-room
# 🏡 3D Vibe Room Simulator

[![GitHub Pages Deployment Status](https://img.shields.io/github/deployments/haheehee/my-3d-room/github-pages?label=GitHub%20Pages&logo=github)](https://haheehee.github.io/my-3d-room/)

**3D Vibe Room Simulator** is a simple web browser-based 3D space design tool. Without complicated installation, you can quickly visualize your own space layout by setting room dimensions and placing furniture, doors, and windows.

## ✨ Key Features

* **📏 Room Customization:** Create a room of any desired size by directly inputting the width (W), height (H), and depth (D).
* **🛋️ Drag & Drop Placement:** Easily place furniture inside the room and move objects using simple mouse operations.
* **🚪 Door/Window Implementation:** Place door or window objects on walls and configure the swing direction (e.g., in-swing, out-swing).
* **⚙️ Integrated Property Modification:** **Double-click** any object (room, furniture, door) to modify all its properties (size, color, swing type) at once in a single modal popup.
* **💾 Save and Load:** Save your current layout to a file and load it anytime to continue your work.

---

## 🚀 How to Use

### A. Creating Rooms and Placing Objects

1.  **🏠 Create New Room:**
    * In the left panel's **'Room Size Setting'** section, enter the `Width (W)`, `Height (H)`, and `Depth (D)` values in meters.
    * Click the `🏠 Create New Room` button.

2.  **🛋️ Place Furniture:**
    * In the left panel's **'Add Furniture'** section, select the room you wish to place the object in.
    * Set the furniture's `Width (W)`, `Height (H)`, `Depth (D)`, and its color.
    * Click the `Place Furniture (+)` button to add the furniture to the center of the room.

3.  **🚪 Place Door/Window:**
    * In the left panel's **'Door/Window Placement'** section, select the room.
    * Select the door width (W), the wall for placement, and the hinge/swing type (e.g., `L_IN`).
    * Click the `🚪 Place Door (+)` button.

### B. Object Manipulation and Modification

| Action | Target | Description |
| :--- | :--- | :--- |
| **Double Click** | Room, Furniture, Door | Opens the **Integrated Property Modification Modal** to edit size, color, swing type, etc., all at once. |
| **Mouse Drag** | (Empty Space) | Rotates the 3D viewpoint (camera). |
| **Shift + Drag** | Furniture, Door | Moves the object on the **horizontal plane**. |
| **Ctrl + Drag** | Furniture | Moves the object **vertically** (up/down). |
| **Alt + Shift + Drag** | Room | Moves the entire room on the horizontal plane. |

---

## 🛠️ Development Environment

This project is implemented using only client-side technologies without the need for a separate server-side script.

* **HTML5 / CSS / JavaScript:** Basic structure and logic
* **Three.js (r128):** 3D rendering engine
* **OrbitControls:** Mouse-based 3D viewpoint control

---

## 🔗 Project Links

| Category | Address |
| :--- | :--- |
| **Live Demo** | **[Click here to run the simulator]**(https://haheehee.github.io/my-3d-room/) |
| **GitHub Repository** | [https://github.com/haheehee/my-3d-room/](https://github.com/haheehee/my-3d-room/) |

---

## 📄 License

MIT License
