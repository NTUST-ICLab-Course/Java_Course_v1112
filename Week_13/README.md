# Week_13

## Unit2 §3 Animation (Cont’d)
   * Unit2 Lab18
      * 影片：https://youtu.be/NosC7cgiZ2M
   * Unit2 Lab19   
      * 影片：https://youtu.be/gvSU9uLLQ50
   * Unit2 Lab20
      * 影片：https://youtu.be/OKsBctfzupQ
   * Packaging and accessing runtime resources in a runnable jar
      * 影片：https://youtu.be/RusMB6R5DJ0
## 【Lab18-20 的開場】
  * Lab18-Lab20 開場
      * 影片：https://youtu.be/a7x5DlbEPg0
  1. 關於 Driver 與 Panel 的分工：<br>
  其實可以合併，也就是讓 Driver去繼承 JPanel。我們以 Lab01為例。參考Lab01New。
  2. 觀摩別人寫的類別：<br>
  Lab18是要我們從無到有造一個 Turtle 的類別，但是之前 Lab06就已經有使用一個 Turtle class了。等大家試完 Lab18之後，再偷看一下，當時課本-的作者是怎麼寫的程式。還記得怎麼用 F3 來看某類別的定義 (code)。
## 【分析 Bucket, Turtle, Robot and Display 類別的專業寫法】
  *
     * 影片：https://youtu.be/OCGkHzvQHuU
  3. 另外一招合併原本 Driver 與 Panel 的分工：<br>
     讓主角類別自己準備舞台。像Lab04中的 Bucker 的類別中，由類別自己來定義畫圖所需要的 JPanel 與 JFrame。我們看 Lab04中的 Bucket 為例，我們可以使用 BucketDriver 來畫 JFrame以及裏面的 JPanel的圖
  4. 會了 Turtle之後，再來看 Unit1 的 Robot以及 Display這兩類別：<br>
當我們在 Unit1的 Lab00時，怎麼可以這麼簡單就畫出一個視窗，然後裏面有一個 Robot 的物件顯示出來？仍然還是一樣由F3進去看code。
## 解答
  * Lab 解答影片
      * Unit2 Lab18 Ans : https://youtu.be/nVob8LcjD3Y
      * Unit2 Lab19 Ans : https://youtu.be/5nix9Gk229I
      * Unit2 Lab20 Ans : https://youtu.be/whV2U2TtjKs
