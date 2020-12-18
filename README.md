# Test 1

Output will be -5;

```php
/*
(int)$_GET is 25;
$e is declared after function declaration but accessed though global in the function call;
Hence operation will be : 5+25-25-10 > -5
*/
```

# Test 2

```php
/* ------------------------------------------------------------------------------
I have to be honnest and i'm not the kind for mathematics and algorythms.
Price to pay for having done Litterature cursus at school.
I do train quite some bit over Hackerank though;
------------------------------------------------------------------------------ */

function recursiveToGetFactorial($currentN){
    if( !$currentN ){ 
        return 1;
    }
    return $currentN * recursiveToGetFactorial($currentN - 1);
}

// echo recursiveToGetFactorial(n);

```

# Test 3

```php
/* ------------------------------------------------------------------------------
Method overriding is creating a child class which inherits from it's parents;
You can then declare the same method($args) in the child class to change the behaviour of the method, adding / modifying output.
You can also call the parent method by parent::method(); 
------------------------------------------------------------------------------ */
class A{
  public function echoHW(){
    echo 'Hello World';
   }
}

class B extends A{
  public function echoHW(){
    echo 'World Hello';
  }
}

$a = new A;
$b = new B;

$a->echoHW();   // Ouput 'Hello World';
$b->echoHW();   // Output 'World Hello';
```

# Test 4

```bash
The alternative of inheritance would be composition, using interfaces and implementing them into classes.
This has the added value of being able to use the same interface(s) on different Classes that would share some methods but not all of them.

// Sorry, no UML with a readme format
```

# Test 5

```php
/* ------------------------------------------------------------------------------
SQL injection is a known method to gain access to data through badly coded scripts or unescaped requests.
The most basic would be using WHERE ? and injecting  " OR 1=1 ", having true as a result hence being able to get the results.
Another dangerous manipulation would also be chaining request with "; Any operation like DROP/TRUNCATE" etc.

Methods to preventing it is to first escape content and used prepared statement.
Obvisouly also having a SQL user which has no root and total PRIVILEGES
------------------------------------------------------------------------------ */
```

# Test 6

```php
/* ------------------------------------------------------------------------------
I'm not sure if this is a tricky question or a typo in the example but <? instead of <?php would basically print the code instead of executing it on recent versions of PHP.
IF not, the concept of closures is "anonymous" functions you declare as callbacks, and i'd be happy to resvole it with my calculator !
------------------------------------------------------------------------------ */
```
