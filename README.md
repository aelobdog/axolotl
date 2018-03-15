
# Axolotl 

 __Axolotl__ is a _pseudo -_ programming langauge.


For those of you familiar with markdown, Axolotl is similar to Markdown, but instead of dealing with HTML it deals with numerous other languages.

Axolotl takes it's input in a simplified tag-based syntax and converts it to your language of choice.

You can write code along with Axolotl code as Axolotl has limited functionality and is designed primarily as an educational tool and a utility which helps in the creation of easily readable code in a fast way.

Axolotl is still in it's beta stages.



```sh
$ cat input
<d] Hello World ! [d>
$ touch output
$ cat output
$ axolotl input output java
Enter name of class   : HelloWorld!                
$ cat output 
```
```Java
import java.util.*;
import java.io.*;


class HelloWorld!
{
public static void main(String args[]) throws Exception
{

Scanner sc=new Scanner(System.in);


System.out.println(" Hello World ! ");

}
}
$ 
``` 

INSTALLATION

In order to use Axolotl you need to perform a few steps.
If you're using git, you can clone the project into your directory of choice by doing :

```sh
$ git clone https://github.com/ashvin-godbole/axolotl.git
$ cd axolotl/bin/
$ java Axolotl // Note that the program will prompt you the right syntax.
```
