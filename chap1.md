# Variables #

Note:

* The variable naming convention in tutorial will follow camel_case.
* This tutorial uses PEP8 spacing convention for Perl as well.
* Python3 in this tutorial refers as Python 3.7.2 and above
* Perl in this tutorial refers as Perl 5.x

## Variable declaration for Perl ##

It is not required to assign variable types the variable for both Perl and Python.

```perl
    #!/usr/bin/perl
    #The variable declaration
    my $num_1 = 1;
    $name_of_my_car = "Mazda";

```

Variable declaration for Python

```python
    #!/usr/local/bin/python3
    num_1 = 1
    name_of_my_car = "Mazda"
```

## Printing the variable in Perl ##

```perl
    $num_1 = 1;
    print($num_1);

    #Perl style
    print("My favourite number is". $num_1 . "\n");

    #C-style printing
    printf("My favourite number is %d",  $num_1);

```

## Printing the variable in Python ##

```python
    num_1 = 1

    print(num_1)

    car_plate = "XZY 1234"
    car_color = "Red"

    #C-style printing
    print(
        """The color of my car is %s. My plate number is %s.\n
        """ % (car_color, car_plate)
    )
    #Use format to print
    print(
        """
        The color of my car is {0}. My plate number is {1}\n
        """.format(car_color, car_plate)
    )

    #Use f-string to print
    print(
        """
        The color of my car is {car_color}. My plate number is {car_plate}\n
        """
    )
```

## Casting in Perl ##

```perl

    #From String to Int
    $a = "1";
    $a = int($a);

    #From String to Float
    $a = "1.23";
    $a = printf("%.2f", $a);

    #From Float to String
    $a = sprinf("%s", $a);
```

## Casting in Python ##

```python

    #From String to Int

    a_str = "1"
    a = int(a_str)

    #From Int to Float

    a = float(a)

    #From Float to String

    a = str(a)

    """
    There are no double, long, unsigned (long, int) in Python
    """
```
