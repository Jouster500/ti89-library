# ti89-library
A library of ti89 (titanium) functions I have built and would like preserved for years to come and others to use. 

It is my belief that the ti line of calculators is severely under utilized tool for fields of science and mathematics. 
Being in the CS profession, I view it as an excellent source for containing or making use of machine learning algorithms.
The problem is there are a number of limitations as well as the need to actually program the functions in the first place.

This library contains a number of functions which are built with the aim of being as minimalistic as possible, making use
of redundant code as much as possible, and utilizing functions as much as possible. I recognize that in time these programs will
become obsolete, but it is my hope that I can document at least some of the functions I made with the technology available that with
a few tweaks in the future, can be modified for future iterations. At the very least, it serves as a backup repo in case the calculator
becomes damaged, lost, or simply unable to repair. 
__________________
Following that, folders reflect the system hierarchy of different folders, and that referencing programs or functions from other programs is
denoted as `folder/namespace`. 

The design philosophy implemented in revolves around the fact that memory on the calculators is limited, and ideally we want to be able to program
things as fast as possible without a dedicated keyboard. Reference lookups should theoretically result in less memory needed for a given function
and as a result yield a smaller footprint in general.

`tibasic` is not something that seems to be supported, and I lack the knowhow for actually moving files between the calculator and my computer. 
Therefore, all tibasic programs contained herein will follow their readable versions, handtyped and provided as they are in the actual code.
Do note the following
```
// Some comments about this program thats not actually within the program
namespace(vars)
Func
...
EndFunc
```

Unless specified, each line begins with `:`. Lines starting with `//` or `/** */` are just comments that I did not directly include in the program as its intended to save space.
They are just comments by which I can inform myself or anyone else reading this the purpose of this particular function. 
