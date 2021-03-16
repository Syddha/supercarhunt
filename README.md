/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package siddharth.kanoje.pkg201901965;

import java.util.Scanner;

public class SiddharthKanoje201901965 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Please enter the name: ");
        String name=sc.nextLine();
        System.out.print("Please enter your Student id: ");
         int student_id = sc.nextInt();
         System.out.print("Please enter the number 1: ");
         int number_1 = sc.nextInt();
         System.out.print("Please enter the number 2: ");
         int number_2 = sc.nextInt();
         System.out.print("Please enter the number 3: ");
         int number_3 = sc.nextInt();
         if(number_1 >number_2){
             if(number_1>number_3){
                 System.out.println("The greatest number is: "+number_1);         }
             else{
                 System.out.println("The greatest number is: "+number_3);} }
             else{
                     if(number_2>number_3){
                      System.out.println("The greatest number is: "+number_2);  }
                     else{
                 System.out.println("The greatest number is: "+number_3); } }}   }

    

