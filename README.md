Calculator built in Jack, a simple OOP similar to Java, based on Nand2Tetris textbook

Note: In order to use, you will need to download tools from the Nand2Tetris open-source textbook linked below: 

https://drive.google.com/file/d/1xZzcMIUETv3u3sdpM_oTJSTetpVee3KZ/view

Tools you'll need to download from link above to run calculator: VMEmulator (used to run the compiled virtual machine code), JackCompiler (to compile the Jack code to VM code)

    Functions that are available on calculator using Reverse Polish Notation (similar to a stack): 
        addition (put two numbers on the stack, and use the "+" key, and it will pop the two numbers, and push the sum on the stack),
        subtraction (same as addition, except trigger is "-" key),
        multiplication (trigger is "*" key),
        division (trigger is "/" key),
        e'th exponent (pop one number from the stack, x, and pushes the value of e^x, trigger is "W" key), 
        natural log (pushes the natural log of the top number in stack, trigger is "L" key), 
        root function (pops top two numbers, x and y, and pushes x^(1/y), trigger is "R" key),
        power (pops two numbers, x and y, and pushes x^y, trigger is "^" key),
        sin, cos, tan (pops one number, and pushes the value of the trig functions on the stack, triggers are "S", "C", "T" respectfully),
    

    Other things to note: 
        Returns answer with a precision of a pre-set variable "precision", default set to 16. 
        Includes Pi and e (triggers are "P" and "E" respectfully).
        Can calculate signs.
        Multiplication and division are done without using any methods in libraries, only through repeated addition and subtraction.
        Made to run on an 8085 Intel microprocessor with 32kb of ram, so the speed is fairly slow compared to more modern calculators.
        Uses mathematical summation approximates to calculate advanced functions, so it may variate slightly with higher numbers.
        
        

