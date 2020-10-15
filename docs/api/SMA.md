###### PHEXT > [DataKit](../README.md) > [API Reference](index.md) > SMA
------
### SMA
A simple class for management of a Simple Moving Average. It works by alternating between adding new values to the array and calculating the current average.
#### Methods
[__construct](#__construct)
[add](#add)
[result](#result)
[__toString](#__tostring)

------
##### __construct
```php
public function __construct(int $maxItems) 
```
Construct a new SMA with the specified maximum number of values.


------
##### add
```php
public function add($value) 
```
Add a new value to the SMA. The value must be numerical in nature.


------
##### result
```php
public function result(int $precision = null) 
```
Return the calculated result of the SMA as it currently stands. You can optionally pass in a value to $precision to control the amount of decimal places that the result is rounded to.


------
##### __toString
```php
public function __toString() 
```
No documentation available.


------