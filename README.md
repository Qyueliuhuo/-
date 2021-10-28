# -1.package com.leo.demo;

public class Demo07 {
 
 int a;
 double b;
 
 public void foo1() {
  
  //定义变量  局部变量
  //语法： 数据类型  变量名 = 初始值；
  int money = 20000;
  
  System.out.println(money);
  System.out.println(a);
 }
 
 public void foo2() {
  System.out.println(a);
  System.out.println(b);
 
 }
 
 public void foo3() {
  int i = 1;
  System.out.println(i);
  System.out.println("i");
 }
 public static void main(String[] args) {
  Demo07 demo = new Demo07();
  demo.foo3();
  
 
 }
 
}
