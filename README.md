# HelloWorld
JAVA第一接触
一)JAVA概述
  JDK java的开发工具包+JRE
  JRE java的程序运行环境+JVM
  JVM java的程序虚拟机
  
  JAVAC 负责编译的部分，但执行javac时会启动java编译器程序，对指定扩展名的.java文件进行编译，生成.class字节码文件
  java  负责运行的程序，会启动
  
  
  闰年的判断公式：
    1）能被4整除，并且，不能被100整除
    或者
    2）能被400整除
    
    
    /*
    使用三目运算，scanner方法。
    判断用户输入年份是平年，闰年
    */
    Scanner scan=new Scanner(System.in);
		System.out.println("请输入一个年份：");
		int year=scan.nextInt();
		System.out.println("您输入的年份为："+year);
		
		boolean flag=(year%4==0 && year%100!=0)||year%400==0;
		String str= flag ? year+"是闰年" : year+"是平年";
		System.out.println(str);
   /*
   使用if语句判断用户输入的年份是平年还是闰年
   */
    if(year%4==0 &&year%100!=0 ||year%400==0) {
			System.out.print("闰年");
		}else{
		System.out.print("平年");
		}
    
    
    
    
