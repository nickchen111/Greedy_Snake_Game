# Greedy_Snake_Game
# 資料夾說明
* 貪吃蛇遊戲:
  * 遊戲說明: 玩家需要用上下左右鍵操作貪吃蛇去吃到畫面中隨機出現的果實,並且每次吃了果實尾巴就會變長分數就會增加 如果咬到自己遊戲就結束了
  * 結合HTML與CSS做出遊戲畫面,再利用Javascript物件導向概念做出果實、蛇身等物件
  * 遊戲畫面:
    <img height="400" width="300" src="https://github.com/nickchen111/Greedy_Snake_Game/blob/main/img/%E8%B2%AA%E5%90%83%E8%9B%87.png">
    亦有github page可以實際使用
  * 技術細節:
    * 需考量果實每次出現地點不能在貪吃蛇身體上 利用 do while迴圈判斷
    * 利用canvas做出遊戲畫面
    * 需debug玩家如果同時在0.1內按了兩次方向鍵有可能導致的bug處理 利用暫時取消事件監聽功能的方式

# English Version
* Snake Game:
  * Game Description: Players need to use the arrow keys to control a snake to eat randomly appearing fruits on the screen. Each time the snake eats a fruit, its tail grows longer and      the score increases. If the snake bites itself, the game ends.
  * Created the game interface using HTML and CSS, then utilized JavaScript's object-oriented concepts to create objects such as fruits and snake body segments.
  * Technical Details:
    * Need to consider that fruits cannot appear on the snake's body. Use a do-while loop for checking.
    * Implemented the game interface using canvas.
    * Addressed a bug where if players pressed two direction keys within 0.1 seconds, it could cause unexpected behavior by temporarily disabling event listening.
