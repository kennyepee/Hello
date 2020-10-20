# Hello
package com.company;

import com.sun.tools.internal.ws.wsdl.document.soap.SOAPUse;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
	// write your code here
        Scanner keyboard = new Scanner(System.in);
        System.out.print("What is your name? ");
        String input = keyboard.nextLine();
        System.out.println("Hello, " + input);



    }
}
