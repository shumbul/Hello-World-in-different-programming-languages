# Hello-World
The very first thing you’ll do when learning a new programming language is how to make the computer display “Hello, World”.
Let's have a look at how is the quote printed in some familiar programming languages-  ALGOL, Assembly Language, Bash, C, C++, C#, COBOL, FORTAN, Java, JavaScript, Machine Code, MATLAB, ML, NODE.Js, Pascal, Perl, PHP, Python, Ruby, Scala, Swift.

**ALGOL**
BEGIN DISPLAY("HELLO WORLD!") END.

**Assembly language**
```
global  _main
    extern  _printf

    section .text
_main:
    push    message
    call    _printf
    add     esp, 4
    ret
message:
    db  'Hello, World', 10, 0
```

**C**
```
#include <stdio.h>

int main(void)
{
    printf("hello, world\n");
}
```

**C++**
```
#include <iostream>
int main()
{
 std::cout << "Hello, world!\n";
 return 0;
}
```
  
**C#**
```
using System;
class Program
{
 static void Main(string[] args)
 {
 Console.WriteLine("Hello, world!");
 }
}
```

**COBOL**
```
 IDENTIFICATION DIVISION.
 PROGRAM-ID. hello-world.
 PROCEDURE DIVISION.
 DISPLAY "Hello, world!".
```

**FORTAN**
```
program helloworld
 print *, "Hello world!"
end program helloworld
Java
class HelloWorldApp {
 public static void main(String[] args) {
 System.out.println("Hello World!"); // Prints the string to the console.
 }
}

```

**JavaScript**
```
console.log("Hello World!");
Machine code
b8 21 0a 00 00 #moving "!\n" into eax
a3 0c 10 00 06 #moving eax into first memory location
b8 6f 72 6c 64 #moving "orld" into eax
a3 08 10 00 06 #moving eax into next memory location
b8 6f 2c 20 57 #moving "o, W" into eax
a3 04 10 00 06 #moving eax into next memory location
b8 48 65 6c 6c #moving "Hell" into eax
a3 00 10 00 06 #moving eax into next memory location
b9 00 10 00 06 #moving pointer to start of memory location into ecx
ba 10 00 00 00 #moving string size into edx
bb 01 00 00 00 #moving "stdout" number to ebx
b8 04 00 00 00 #moving "print out" syscall number to eax
cd 80 #calling the linux kernel to execute our print to stdout
b8 01 00 00 00 #moving "sys_exit" call number to eax
cd 80 #executing it via linux sys_call

```

**Mathematica (Wolfram Language)**
```
CloudDeploy["Hello, World"]

```

**MATLAB**
```
classdef hello
 methods
 function greet(this)
 disp('Hello, World')
 end
 end
end

```

**ML**
```
print "Hello world!\n";

```

**Node.Js**
```
console.log("Hello World!");

```

**Pascal**
```
program HelloWorld(output);
begin
 Write('Hello, world!')
end.

```

**Perl**
```
print "Hello, World!\n";

```

**PHP**
```
<?php echo "Hello, World";

```

**Python**
```
print("Hello World")

```

**Ruby**
```
puts 'Hello World!'

```

**Rust**
```
fn main() {
 println!("Hello, world!");
}
```

**Scala**
```
object HelloWorld extends App {
 println("Hello, World!")
 }
```

**Swift**
```
println("Hello, world!")
```
