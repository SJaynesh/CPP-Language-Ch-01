# 1. Introduction To C++

<br><br>

  ###  - History of C++ :

  <br>

  > * History of c++ language is interesting to know. Here we are going to discuss brief history of c++ language.
  > * C++ programming language was developed in 1980 by Bjarne Stroustrup at bell laboratories of AT&T (American Telephone & Telegraph), located in U.S.A.
  >
  >     *  Bjarne Stroustrup is known as the founder of C++ language.
  >     *  It was develop for adding a feature of OOP(Object Oriented Programming)in C without significantly changing the C component.  
  >     *  Bjarne Stroustrup  PhD- in OOP's - Object Oriented Programming.
  >     *  C Language is POP :- Procedural Oriented Programming.

<br>

   <p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-01/assets/115562979/4db1967d-44c1-4b45-8d37-89dd387247d6.png" width=80% height=60%></p>

   <br>

  #### Bjarne Stroustrup :

<br>

  <p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-01/assets/115562979/da3efb82-7785-492e-931d-6cbcfc4448b9.png" width=45% height=20%></p>

  <br>

  #### All History of C++ :  

  <br>
  
  <p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-01/assets/115562979/d3bc2454-6064-46fe-95c1-76ef4417b69f.png" width=70% height=40%></p>   

  <br><br>


   ###  -  Difference between C & C++ :

   C | C++
  -------- | -----------
  C is Procedural Oriented Programming. | C++ is a  Object Oriented Programming.
  C programming files are stored with .c extension. | C++ programming files are stored with .cpp extension.
  C is use <stdio.h> header file. | C++ is use <iostream.h> header file.
  C is use for void main() function. Its body for C Language. | C++ is use for int main() function. Its body for C++ Language.
  C is Support only for int,char,float datatype. | C++ is Support for int,char,float,double,string,boolean(True,False).
  No built-in support for classes and object. | Has built-in support for classes and object.


  ## Header File In C++ Language :
  
  > `iostream.h` => standard input-output stream header file
  >
  > `Note : ` => use for<br><br>
  >  #include<iostream.h>  // only support for Turbo C++ <br>
  >  #include<iostream<iostream>>    // only support for Dev C++
  


  ### - cout object :
  > * Print any Message so Use for cout object.
  <pre>
    int main()
    {
        cout << "Hello World !!";  
    }

          Note : 
            << - Insertion Operator.
            cout - console output.
  </pre>

   ### - cin object :
  > * get value from the user to use cin object.
  <pre>
    int main()
    {
        int a,b;
        cout << "Enter a : ";
        cin >> a;
        cout << "Enter b : ";
        cin >> b;
    }

          Note : 
            >> - Extraction Operator.
            cin - console input.
  </pre>

   ###  - using namespace std :

   > From STD come two objects, cout and cin.
  <pre>
    #include <<iostream>iostream>
    int main()
    {
      cout << "Hello World";     // => Throw Error because cout come for std.
    }


    #include <<iostream>iostream>
    int main()
    {
      std::cout << "Hello World";     // => To Print Hello World. std is class. :: => Scope resulation Operator
    }
  </pre>

  <pre>
    #include<<iostream>iostream>
    using namespace std;

    int main()
    {
        cout << "Hello Jaynesh Sarkar.";
        cout << "How are You ?? ";
    }
  </pre>

  ### Escape Sequence Character :
  > `\n` : New Line<br>
  > `\t` : Tab<br>

  <br>
  
  ### `endl` : 
  > * endl is keyword.
  > * endl means End Line. One type of new line.
  > * endl is also called Manipulator.

<br><br>
  > `string` : New Datatype for string. 

  

