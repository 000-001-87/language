# Escha
## Description
Escha is a Scheme-based programming language where everything, from assignments to conditionals, are expressions. It is used as one of the main programming languages in PureSys
for programs.
## Examples
### Hello World
```
(start program "Hello World")
   (display "Hello World!")
(end program)
```
### Multi-threaded
```
(import thread)
(start program "Multithread")
  (for 3)(thread create)
  (thread on_create)
    (display "This is a thread program")
  (end thread)
(end program)
```
  
