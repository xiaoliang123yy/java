# java
package test;

import java.util.Scanner;

public class test1 {
	public static void main(String[] args) {
		//变量定义
		int i;
		
		//变量输入
		System.out.println("输入三角形层数：");
		Scanner scan = new Scanner(System.in);
		i = scan.nextInt();
		
		for(int m = 1;m <= i; m++){
			for(int j = 1;j <= 5 - m;j++){
			System.out.print(" ");
			}
			for(int j = 1;j <= m;j++){
				System.out.print("* ");
			}
			System.out.println(" ");
		}
	}
}

