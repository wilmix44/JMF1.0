# JMF Framework
================

JavaManagementFramework(JMF)     is  invented   by   wilmix jemin  j    at  Jdk1.8.




SYNTAX
=======

<JMF>

<J>


public class <CLASSNAME> {

public  static void  main(String args[])
{

<!  JMF LOGIC !>


}

}


</JMF>



Note: <J>  to  load   JAVA  packages  
=====




ADVANTAGES of USING JMF  Framework Project
==========================================


A)  It   is opensource   and  it  is  used   for  MANAGEMENT  PROJECTS  

for  webapplication.

B)  It  has  attractive syntax 

c)  It   tells   the  developer  to  study  ony  core  java- jdk1.8 concepts

d) SAVES  TIME  AND  COST

E)  It  is also  used as  a mobile  web  application

F) It  has  JMF - Hiber, JMF - Servlet and  follow  MVC  pattern

MVC  pattern  is  userdefined type.

G) We   can  use   with Jquery ,Javascript  for  validation.

h) It  is  used  for developing enterprise  webapplication  to  be  used     with  struts/ spring /spring  boot and  hibernate.

eg)   WTALLY  is  designed  Using   JMF  framework

i)  It  helps   developers   to  develop  a   enterprise webapplication  as  fast  as   could.

j)  When  used    with  OAKJAVA7   can   eliminate   the  demerits   of  java/j2ee.

Provide  much  more     code security  when  used  with OAKJAVA7.

k)  Easy  to   Debug  and  Learnable  framework.


EXAMPLE-1: index.JMF
=====================

<JMF>




public class index {

public  static void  main(String args[])
{


HTML.displayhtml("Register.html"); //  HTML.displayhtml  to   display  //the  contents  of  html;  not  this  is  otherwise known  as  JMF //Servlet 



}

}





</JMF>



Jquerytest.JMF
==============


<JMF>

import  java.util.*;

import jxl.read.biff.BiffException;
import java.io.*;
public  classJquerytest

{
public  static  void  main(String args[]) throws  BiffException,IOException,Exception

{



ArrayList<String> arm1= new  ArrayList<String>();

arm1.add("name");
arm1.add("uname");arm1.add("password");

//  Add    three  fields   name ,uname ,password  of  Register.html
arm1.add("!");




ArrayList<String>armg=SPLITREQUEST.RESULT(arm1,"index.dsn",3,1);

// SPIT the  JMF Page  Request  and  store it  in  arraylist
//  3  indicates  3  fields  of  Register.html
//  1  indicates  increment  counter  by  1


///  Print   the  data   from  register  form  in  table  format

System.out.println("<table style='width:100%' bgcolor=gold>");
// JMF  Servlet
System.out.println("<tr>");



System.out.println("  <th>Name</th>");

System.out.println("  <th>Username</th>"); 

System.out.println("  <th>Password</th>");


System.out.println(" </tr>");

System.out.println(" <tr>");



for (inti=0;i<armg.size();i++)
{


System.out.println("<td>"+armg.get(i)+"</td>");

 }


System.out.println(" </tr>");


System.out.println("</table>");





}
}


</JMF>



