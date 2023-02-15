# Week_03

## Unit1 §2 Inheritance and Methods
   * Static Methods (2020.03.18)
      * 影片：https://youtu.be/Xw8PQTTKnUU
   * Flow Control (2020.03.18)       
      * 影片：https://youtu.be/h0YrJaoCghk
   * JOptionPane (2020.03.18) 
      * 影片：https://youtu.be/b7C1GgudBO8
   * FCPS Unit1 Lab05~Lab06
      * 影片：https://youtu.be/JKUYIzvwuMw
   * MapBuilder
      * 影片：https://youtu.be/5L5TknNHq2c
   * EclipseDebug
      * 影片：https://youtu.be/nBfycTLG814
## 【第三週 2022/3/2 Lab05~Lab07 (Page-29)】
1. Syllabus https://github.com/NTUST-ICLab-Course/JAVA_Course_v1102
2. Check Exercise, Part 1, page 17, on Newlab on class methods (or functions)
3. New page 18, functions as class methods
    * Java Math API: https://docs.oracle.com/....../docs/api/java/lang/Math.html
4. Page 21: Racer API https://compsci.sites.tjhsst.edu/CSweb/Unit1/api/index.html
Create Unit1\Racer.java
5. Page 23: Robot API for interesting Boolean methods
6. Page 24: rebel to hard-coded: Use JOptionPane.showInputDialogto include a flexible map
Hard-coded:
Display.openWorld("maps/tasks1.map");
Flexible JOptionPane:
String filename = JOptionPane.showInputDialog("What robot map?");
Display.openWorld("maps/" + filename + ".map");
7. A better yet option:
https://mkyong.com/....../java-swing-joptionpane....../
Object[] maps = { "tasks1", "tasks2", "tasks3" };
String filename = (String) JOptionPane.showInputDialog(null, "What robot world?", null, JOptionPane.PLAIN_MESSAGE, new ImageIcon(), maps, "tasks1");
Display.openWorld("maps/" + filename + ".map");
8. ○ Robot ophelia = new Athlete();
Robot ophelia;
new Robot();
=
9. X Athlete ophelia = new Robot();
10. ○ Climber karel = new HillClimber();
Climber karel;
new HillClimber();
11. Page 24: count and print the number of beepers
int count = 0;
count++;
System.out.println("Count in task_04 is " + count);
12. Page 25: more exercise tasks
BuildMap.jar D:\Google雲端硬碟\Java2020Spring-workSpace\Unit1
When you save, you must type in the name and the extension .map
13. Page 26: Load Mountain.java and study its method explore
14. Page 28: Polymorphism: the compiler (in this case) allows a superclass reference to a subclass object.
  * 2022/3/2 上課影片
    * 影片_1：https://youtu.be/8-teP_GEpv4
    * 影片_2：https://youtu.be/ZI3jkHO2Pj0
 
## 解答
  * Lab 解答影片
      * Unit1 Lab05 Ans：https://youtu.be/TnicxohFT5o
      * Unit1 Lab06 Ans：https://youtu.be/9_czB2AxUv4
      * Unit1 Lab07 Ans：https://youtu.be/8qNiUXy1GBE
