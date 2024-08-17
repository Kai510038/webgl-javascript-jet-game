# webgl_javascript_jet_game
1. Jet game
https://www.youtube.com/watch?v=VGKaVB6e7Z4&feature=youtu.be
# WASD 鍵控制飛機方向與速度  
## WASD-Controlled Airplane Direction and Speed

## 功能 | Features
本專案使用 WASD 鍵來控制飛機的方向與速度，並結合其他遊戲功能。  
This project uses the WASD keys to control the airplane's direction and speed, along with other game mechanics.

- **方向與速度控制 | Direction and Speed Control**:  
  - W/S 鍵控制飛機的速度加減。  
    W/S keys control the increase and decrease of speed.
  - A/D 鍵控制飛機的左右平轉。  
    A/D keys control the airplane's left and right roll.

- **指針尋找最近的大頭 | Pointer to Nearest Target**:  
  - 指針自動尋找並指向最近的大頭位置。  
    A pointer automatically locates and points to the nearest "big head" target.

- **大頭隨機生成 | Random Target Generation**:  
  - 大頭會在飛機起飛後隨機生成於上下左右前的某一方向，飛機初始位置位於世界中心。  
    The "big head" target is randomly generated in a direction (up, down, left, right, or front) after takeoff. The airplane starts at the center of the world.

- **大頭持續追蹤 | Target Following**:  
  - 大頭會持續轉向並跟蹤飛機的位置。  
    The target continuously rotates to follow the airplane's position.

- **重新生成 | Regeneration After Collision**:  
  - 當飛機撞擊大頭後，遊戲重新開始，大頭會隨機重新生成。  
    After the airplane collides with the "big head," the game restarts and the target is regenerated randomly.

- **機翼微調 | Wing Fine-Tuning**:  
  - 可透過代碼進行飛機機翼的微調以增強飛行操控 (代碼位置：168~174 行)。  
    Wing fine-tuning can be done to enhance flight control (code lines: 168~174).

- **迷霧效果 | Fog Effect**:  
  - 使用迷霧來模擬距離感，代碼位置：`settings.fogAmount=fog(target[2],z[zz])`。  
    A fog effect is applied to simulate depth, with the relevant code: `settings.fogAmount=fog(target[2],z[zz])`.

- **背景音樂 | Background Music**:  
  - 當玩家開始操作時，自動播放背景音樂以增強沉浸感。  
    Background music automatically plays when the player starts controlling the airplane for added immersion.

---



<img width="642" alt="螢幕擷取畫面 2023-04-21 113705" src="https://user-images.githubusercontent.com/79260866/233535144-874c255c-e277-485d-80e6-3483b03195f2.png">
<img width="640" alt="螢幕擷取畫面 2023-04-21 113648" src="https://user-images.githubusercontent.com/79260866/233535152-b044f450-ca5f-491f-b7bc-dea157a4919f.png">


2. snake game
![186576800-9eeb4799-950c-41e9-b451-53c1e587de69](https://user-images.githubusercontent.com/79260866/233534880-c15eb1c3-3f97-4370-be3e-cb9aaffd2a02.png)
![175522027-995df8c0-7e3f-48d2-b980-69b3cc7d4554](https://user-images.githubusercontent.com/79260866/233534881-d72ffd5f-130b-46d5-ba32-09d69ba0bd29.png)
