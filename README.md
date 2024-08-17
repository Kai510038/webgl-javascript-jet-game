# webgl_javascript_jet_game

## Demo Links
https://kayla956593.github.io/1/1.html
[Jet Game Video](https://www.youtube.com/watch?v=VGKaVB6e7Z4&feature=youtu.be)

## 效果圖 | Effect Picture
![image](https://github.com/user-attachments/assets/cfe556ae-75c9-4ab7-9541-17b4e614a020)

## 功能 | Features
- **控制方式 | Controls**:  
  使用 `WASD` 鍵來控制飛機的方向與速度。  
  Use the `WASD` keys to control the direction and speed of the jet.  
  - `W` / `S`: 控制飛機的速度  
    Control the jet’s speed (up/down)
  - `A` / `D`: 控制飛機的左右平轉  
    Control the jet’s roll (left/right)

- **尋找大頭 | Big Head Targeting**:  
  指針會自動尋找最近的「大頭」目標。  
  A pointer automatically guides the player to the nearest “big head” target.

- **大頭生成 | Big Head Generation**:  
  「大頭」會隨機生成在上下左右前的位置，飛機起飛點位於世界中心。  
  Big heads are randomly generated in different directions (up, down, left, right, front). The jet starts at the center of the world.

- **大頭追蹤 | Big Head Tracking**:  
  大頭會持續轉向飛機的方向。  
  The big head continuously rotates to face the jet’s position.

- **重新開始 | Game Reset**:  
  當飛機撞擊大頭時，遊戲會重新開始，大頭會重新生成。  
  When the jet collides with the big head, the game restarts, and a new big head is generated.

- **機翼微調 | Wing Adjustment**:  
  微調飛機的機翼設定，程式碼行號 168~174。  
  Fine-tune the jet's wing configuration in code lines 168-174.

- **迷霧效果 | Fog Effect**:  
  添加迷霧效果，設定 `settings.fogAmount=fog(target[2],z[zz])`。  
  A fog effect is implemented with `settings.fogAmount=fog(target[2],z[zz])`.

- **背景音樂 | Background Music**:  
  當玩家開始操作時，會播放背景音樂。  
  Background music plays when the player begins controlling the jet.

## 程式執行流程 | Game Logic Flow
1. 玩家使用 `WASD` 鍵控制飛機的移動與速度。  
   The player uses the `WASD` keys to control the jet’s movement and speed.
2. 指針會引導飛機尋找最近的大頭。  
   A pointer guides the jet toward the nearest big head.
3. 當飛機撞擊大頭後，遊戲重新開始，大頭重新生成在隨機位置。  
   Upon collision with the big head, the game restarts, and the big head is regenerated at a random location.
4. 遊戲中會有迷霧效果，增加沉浸感。  
   Fog effects enhance the immersive experience during gameplay.

## 參考資源 | References
- https://webgl2fundamentals.org/

---

## 開發過程與挑戰 | Development Process and Challenges
此專案最具挑戰的部分是實現飛機控制與大頭追蹤邏輯。飛機的速度與方向控制需要精準的數學運算，而大頭持續追蹤飛機的位置則需要使用 3D 向量計算。此外，加入迷霧效果與背景音樂增強了遊戲的視覺與聽覺體驗。這些細節花費了大量時間進行調整，特別是在平衡遊戲的流暢度與視覺效果方面。

---

The most challenging part of this project was implementing the jet's control system and the logic for tracking the big head. Precise mathematical calculations were required to control the jet's speed and direction, while 3D vector math was used for the continuous tracking of the big head toward the jet. Additionally, the fog effect and background music enhanced the visual and auditory experience. Adjusting these details took a lot of time, especially in balancing the smoothness of the game with visual effects.
