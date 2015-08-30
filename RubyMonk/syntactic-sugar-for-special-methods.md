## Syntactic Sugar for Special Methods

- you've probably noticed that in the last lesson, Integer objects list mathematical operators like + and - among their methods. You probably also thought to yourself that invoking the + method like so - 1.+(2) - to add two numbers would be... clumsy

`1.+(2)`

> Output:

`3`

- Ruby makes an exception in its syntactic rules for commonly used operators so you don't have to use periods to invoke them on objects.


- There are several other method names that have this special status - here's a quick summary of the ones you're most likely to run into.

`+   -   *   /   =   ==    !=    >   <   >=    <=    []`