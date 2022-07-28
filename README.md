# sacode-phpiii-Day03-project02
### belajar tipe data PHP
 ✅ String <br>
 ✅ Integer <br>
 ✅ Float <br>
 ✅ Boolean <br>
 ✅ Array <br>
 ✅ Object <br>
 ✅ Null <br>

 ### String

```php
<?php

    $a = "Hello World";
    $b = "Hello World";

    echo $a. '<br>'.$b;
    echo "<br>";
    echo $a;
    // echo "<br>";

?>
```

 ### Integer

```php
<?php

$x = 23;
echo $x;
echo "<br>";
var_dump($x);

?>
```

### Float

```php
<?php
$x = 10.134;
var_dump($x);


?>
```

### Boolean

```php
<?php
    $x = true;
    $y = false;

    var_dump($x);

?>
```

### Array

```php
<?php
    $student = array('Samuel','Nick','Archy', 'Delvi');
    foreach($student as $s)
    {
        echo 'Nama ' . $s. "<br>";
    };
 $kelas = ['php I', 'php II', 'php III'];
// var_dump($kelas[0]);
//  var_dump($kelas[1]);
//  var_dump($kelas[2]);

    echo $kelas[1];
?>
```

### Object

```php
<?php
class Car {
    public $color;
    public $model;
    public function __construct($color, $model)
    {
        $this->color = $color;
        $this->model = $model;
    }

    public function message(){
        return "My Car is a " . $this->color. " ". 
            $this->model."!";
    }
}

$myCar = new Car("black", "volvo");
echo $myCar->message();
echo "<br>";
$myCar = new Car("Red", "Toyota");
echo $myCar->message();
?>
```

### Null

```php
<?php
    $x = 'Hello World';
    $x = null;
    $y = 'SaCode';
    var_dump($y);
    $y = 12;
    echo $y;
    var_dump($y);
    $y = null;
    var_dump($y)
?>
```