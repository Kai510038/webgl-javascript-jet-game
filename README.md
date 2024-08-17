# webgl_javascript_jet_game  
## Jet Game

## Demo
[Jet Game Video](https://www.youtube.com/watch?v=VGKaVB6e7Z4&feature=youtu.be)

## 功能 | Features
- **控制方式 | Controls**:  
  使用 `WASD` 鍵來控制飛機的方向與速度。  
  Use `WASD` keys to control the direction and speed of the jet.  
  - `W` / `S`: 控制飛機的速度  
    Control the jet’s speed (up/down)
  - `A` / `D`: 控制飛機的左右平轉  
    Control the jet’s roll (left/right)

- **尋找大頭 | Big Head Targeting**:  
  指針會自動尋找最近的「大頭」目標。  
  A pointer guides the player to the nearest “big head” target.

- **大頭生成 | Big Head Generation**:  
  「大頭」會隨機生成在上下左右前的位置，飛機起飛點位於世界中心。  
  Big heads are randomly generated around the jet (up, down, left, right, front). The jet starts at the center of the world.

- **大頭追蹤 | Big Head Tracking**:  
  大頭會持續轉向飛機的方向。  
  The big head continuously rotates toward the jet’s position.

- **重新開始 | Game Reset**:  
  當飛機撞擊大頭時，遊戲會重新開始，大頭會重新生成。  
  When the jet collides with the big head, the game restarts, and the big head regenerates.

- **機翼微調 | Wing Adjustment**:  
  微調飛機的機翼設定，程式碼行號 168~174。  
  Fine-tune the jet's wing configuration (code lines 168-174).

- **迷霧效果 | Fog Effect**:  
  添加迷霧效果，設定 `settings.fogAmount=fog(target[2],z[zz])`。  
  A fog effect is implemented using `settings.fogAmount=fog(target[2],z[zz])`.

- **背景音樂 | Background Music**:  
  當玩家開始操作時，會播放背景音樂。  
  Background music plays when the player begins to control the jet.

## 程式執行流程 | Game Logic Flow
1. 玩家使用 `WASD` 控制飛機的移動和速度。
2. 指針會引導飛機尋找最近的大頭。
3. 當飛機撞擊大頭後，遊戲重新開始，大頭重新生成在隨機位置。
4. 遊戲中會有迷霧效果，增加沉浸感。

---

## 開發過程與挑戰 | Development Process and Challenges
此專案最具挑戰的部分是實現飛機控制與大頭追蹤邏輯。飛機的速度與方向控制需要精準的數學運算，而大頭持續追蹤飛機的位置則需要使用 3D 向量計算。此外，加入迷霧效果與背景音樂增強了遊戲的視覺與聽覺體驗。這些細節花費了大量時間進行調整，特別是在平衡遊戲的流暢度與視覺效果方面。

<img width="642" alt="螢幕擷取畫面 2023-04-21 113705" src="https://user-images.githubusercontent.com/79260866/233535144-874c255c-e277-485d-80e6-3483b03195f2.png">
<img width="640" alt="螢幕擷取畫面 2023-04-21 113648" src="https://user-images.githubusercontent.com/79260866/233535152-b044f450-ca5f-491f-b7bc-dea157a4919f.png">


2. snake game
![186576800-9eeb4799-950c-41e9-b451-53c1e587de69](https://user-images.githubusercontent.com/79260866/233534880-c15eb1c3-3f97-4370-be3e-cb9aaffd2a02.png)
![175522027-995df8c0-7e3f-48d2-b980-69b3cc7d4554](https://user-images.githubusercontent.com/79260866/233534881-d72ffd5f-130b-46d5-ba32-09d69ba0bd29.png)
