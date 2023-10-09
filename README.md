# 1. Introduction To C++

  ###  - History of C++ :

  > * C++ programming language was developed in 1979 by Bjarne Stroustrup at bell laboratories of AT&T (American Telephone & Telegraph), located in U.S.A.
  >
  >     *  Bjarne Stroustrup  PhD- in OOP's - Object Oriented Programming.
  >     *  C Language is POP :- Procedural Oriented Programming.
  >     *  Bjarne Stroustrup is known as the founder of C++ language.

  #### Bjarne Stroustrup :

  <p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-01/assets/115562979/da3efb82-7785-492e-931d-6cbcfc4448b9.png" width=40% height=30%></p>

  #### All History of C++ :  
  <p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-01/assets/115562979/d3bc2454-6064-46fe-95c1-76ef4417b69f.png" width=40% height=30%></p>    


   ###  -  Difference between C & C++ :

   C | C++
  -------- | -----------
  C is Procedural Oriented Programming. | C++ is a  Object Oriented Programming.
  C programming files are stored with .c extension. | C++ programming files are stored with .cpp extension.
  C is use <stdio.h> header file. | C++ is use <iostream.h> header file.
  C is use for void main() function. Its body for C Language. | C++ is use for int main() function. Its body for C++ Language.
  C is Support only for int,char,float datatype. | C++ is Support for int,char,float,double,string,boolean(True,False).
  No built-in support for classes and object. | Has built-in support for classes and object.


  ## Header File In C Language :
  
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

          Note : << - Insertion Operator
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

          Note : >> - Extraction Operator
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
  > `endl` : New Line Or endline<br>
<br><br>
  > `string` : New Datatype for string. 

  

