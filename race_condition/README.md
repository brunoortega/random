##  **Race Condition**

![GitHub issues][license]

A race condition is an undesirable situation that occurs when a device or system
attempts to perform two or more operations at the same time.

The idea of this example is to teach you how to:

* Use _GitHub_ and _Git_ tool;
* Compile a code using GNU/Linux environment;
* Use a _Makefile_ as a building tool;
* Use markup language at README file (markdown, .md);
* Use license properly with SPDX-License-Identifier in all files;
* Use badges for your project;
* Write modular codes;
* Learn about race condition and semaphores;

### Building C Example

1. Fork this repository on GitHub to your personal account;

2. Clone the repository;
```console
$ git clone https://github.com/<account>/random.git
$ cd random/race_condition/
```

3. Then, compile the example:
```console
$ make
```

### Running C Example

1. Run the unprotect example:
```console
$ ./unprotect
```

1. Run the protect example:
```console
$ ./protect
```

### Challenge (Optional)

* Write this same example in Python and push it to GitHub to further revision.

### References

* http://greenteapress.com/semaphores/LittleBookOfSemaphores.pdf
* https://greenteapress.com/wp/semaphores/

[license]: https://img.shields.io/badge/License-BSD%203--Clause-blue
