# Week_05

## Unit1 §4 Abstract Classes and Interfaces
   * FCPS Unit1 Lab11~Lab12
      * 影片：https://youtu.be/IVBUThXbZk8
   * FCPS Unit1 Lab14~Lab16
      * 影片：https://youtu.be/Xj3WybMRCso
   * AnstractClassAndInterface (2020.04.01) 
      * 影片：https://youtu.be/h4nolii0Mn8
   * SingleTreadToMultiThread (2020.04.08)   
      * 影片：https://youtu.be/JiZIQ_5-oAU
   * Thread (2020.04.08)
      * 影片：https://youtu.be/TDnTPdUwK6s
   * Runnable (2020.04.08)   
      * 影片： https://youtu.be/3NbPVlG2E7c
   * Lab05Thread (2020.04.08)
      * 影片： https://youtu.be/2q3jhd-7RU4


## 【第五週 2022/3/16 Lab11~Lab16 (Page-47)】
1. Syllabus https://github.com/NTUST-ICLab-Course/JAVA_Course_v1102
  * FCPS Unit1 Lab11~Lab12
    * 影片：https://youtu.be/IVBUThXbZk8
  * FCPS Unit1 Lab14~16
      * 影片：https://youtu.be/Xj3WybMRCso
   * AnstractClassAndInterface (2020.04.01) 使用Eclipse的技巧
      * 影片：https://youtu.be/h4nolii0Mn8
   * SingleTreadToMultiThread (2020.04.08)   
      * 影片：https://youtu.be/JiZIQ_5-oAU
   * Thread (2020.04.08)
      * 影片：https://youtu.be/TDnTPdUwK6s
   * Runnable (2020.04.08)   
      * 影片： https://youtu.be/3NbPVlG2E7c
   * Lab05Thread (2020.04.08)
      * 影片： https://youtu.be/2q3jhd-7RU4
2. Page 36: abstract methods
3. Page 37: anonymous object (回想 Page 28中的 new HillClimber()) 還有 (page 16: takeTheField(maria))
4. Page 37: reverse engineering the abstract Digit class https://compsci.sites.tjhsst.edu/CSweb/Unit1/api/index.html
5. Page 38: --able interface contains only abstract methods signatures
6. Page 38: 繼承有遺產的父輩，實踐有理想的口號
public class Harvester extends Robot implements Workable
public class Harvester extends Robot (only onesuperclass) implements Workable (one or more Interface1, … )
7. Page 39: another example of a superclass reference to a subclass object.
8. Page 41: Lab 13 準備加分題An Original fcpsKarel Lab
9. Page 42: Thread 執行緒
  * API for Swimmer: https://compsci.sites.tjhsst.edu/CSweb/Unit1/api/index.html
  * API for Thread: https://docs.oracle.com/....../api/java/lang/Thread.html
  * One of the constructor takes in a Runnable object as parameter: <br>
public Thread(Runnable target) {<br>
this(null, target, "Thread-" + nextThreadNum(), 0);}
10. Page 42: Java interface Runnable
Implementing Runnable is important because a Thread constructor requires a Runnable object as an argument. <br>
public interface Runnable{<br>
/** <br>
*When an object implementing interface {@code Runnable} is used <br>
*to create a thread, starting the thread causes the object's <br>
*{@code run} method to be called in that separately executing <br>
*thread. <br>
*<br>
*The general contract of the method {@code run} is that it may <br>
*take any action whatsoever. <br>
*@see java.lang.Thread#run() <br>
*/ <br>
public abstract void run(); <br>
}



## 解答
  * Lab 解答影片
      * Unit1 Lab11 Ans : https://youtu.be/0n5xWr-uH5Q
      * Unit1 Lab12 Ans : https://youtu.be/fHFhcCOAwHM
      * Unit1 Lab14 Ans : https://youtu.be/_a2wp4HV88E
      * Unit1 Lab15 Ans : https://youtu.be/ql3FNvX7D6o
      * Unit1 Lab16 Ans : https://youtu.be/RMog6hpbV3w
