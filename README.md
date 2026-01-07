## This a start of the complete DSA with java completely from the starting 
## resource used for this is Youtube ---> Kunal Kushwaha(Java+Dsa+Interview Prep course)

## Day1
    --> In the day 1 learned about the flowcharts and pseudocodes 
        -->Flowchart: representing a code in the form of flowcharts 
        -->pseudocode: not writing complete code but writing the logic of the code without considering the syntex

    -->also learned optimized method to find wheather a give number is prime or not 
        --> that method is consider a number "9"
        --- for 9 we need to check all the number less than 9 
        but in optimized method wee need to check only from 2 to sqroot(9) values.
##### how it works 
        conisder 9
        for 12 the factors are 
            1*12=12, 2*6=12 ,3*4=12 , 4*3=12 ,6*2=12, 12*1=12
                here if we observe 1*12 and 12*1, 2*6 and 6*2 are same we are checking twice for that we will check only from 2 to the "sqroot(12)" it decrease the complixity of the code

    --> solved 2 questions in leetcode its complexity was not that much good but started 
            -->Solved question is:"Two sum","palindrome"

###### with this day 1 dsa learning was done #####


## Day2
    -->In the day 2 learned about java architecture & installation

    -->firstly java codes executes like
            --> java file ---compiler take entire file--> converts into bytecode(.class file)--- interpreter ---> machine code

    --> we need jvm to run the .class file(bytecode) this converts into the machine code

     --> this is the reason why java is called platform independent.


-->JDK VS JRE VS JVM VS JIT
    THIS IS IN THE IMAGE.PNG

#### JDK 
    --> It provides an environment that is requried to run the java program
    ---> it consist of JRE+Development tools,a compiler,archiver,docs generator,interpreter/loader
#### JRE
    --> It provides an environment to only run the programs
        --> it consist Liberies and JVM
--after we get .class file class loader loads all the classes needed to execute the program.
--> JVM sends code to byte code verifier to the format of the code.
#### JVM
    --> line by line execution 

--> solved one easy question in leet code 
        Solved Question: "paranthsies validation"