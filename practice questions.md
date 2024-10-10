### 1. Simple Calculator Program in PHP

```php
<?php
// Basic Calculator Program in PHP
$number1 = 10;
$number2 = 5;
$operator = '+'; // Change this to '-', '*', '/', '%' for different operations

switch ($operator) {
    case '+':
        echo "Addition: " . ($number1 + $number2);
        break;
    case '-':
        echo "Subtraction: " . ($number1 - $number2);
        break;
    case '*':
        echo "Multiplication: " . ($number1 * $number2);
        break;
    case '/':
        if ($number2 != 0) {
            echo "Division: " . ($number1 / $number2);
        } else {
            echo "Cannot divide by zero.";
        }
        break;
    case '%':
        echo "Modulus: " . ($number1 % $number2);
        break;
    default:
        echo "Invalid operator.";
}
?>
```

### 2. Program to Check if an Alphabet is a Vowel or Not

#### Using `if` statement
```php
<?php
$char = 'a'; // Input alphabet

if ($char == 'a' || $char == 'e' || $char == 'i' || $char == 'o' || $char == 'u') {
    echo "$char is a vowel.";
} else {
    echo "$char is not a vowel.";
}
?>
```

#### Using `if-else-if` statement
```php
<?php
$char = 'b';

if ($char == 'a') {
    echo "$char is a vowel.";
} elseif ($char == 'e') {
    echo "$char is a vowel.";
} elseif ($char == 'i') {
    echo "$char is a vowel.";
} elseif ($char == 'o') {
    echo "$char is a vowel.";
} elseif ($char == 'u') {
    echo "$char is a vowel.";
} else {
    echo "$char is not a vowel.";
}
?>
```

#### Using `switch` statement
```php
<?php
$char = 'i';

switch ($char) {
    case 'a':
    case 'e':
    case 'i':
    case 'o':
    case 'u':
        echo "$char is a vowel.";
        break;
    default:
        echo "$char is not a vowel.";
}
?>
```

### 3. Check if a Number is Even or Odd Using Conditional Operator

```php
<?php
$number = 10;

$result = ($number % 2 == 0) ? "$number is even." : "$number is odd.";
echo $result;
?>
```

### 4. Program to Prepare Marks Sheet of a Student

```php
<?php
$math = 80;
$english = 70;
$physics = 90;

$obtained_marks = $math + $english + $physics;
$total_marks = 300;
$percentage = ($obtained_marks / $total_marks) * 100;

echo "Obtained Marks: $obtained_marks<br>";
echo "Percentage: $percentage%<br>";

if ($percentage >= 90) {
    echo "Grade: A+";
} elseif ($percentage >= 80) {
    echo "Grade: A";
} elseif ($percentage >= 70) {
    echo "Grade: B";
} elseif ($percentage >= 60) {
    echo "Grade: C";
} else {
    echo "Grade: F";
}
?>
```

### 5. Program to Check if a Number is in the Range of 1 to 100

```php
<?php
$number = 120; // Input number

if ($number >= 1 && $number <= 100) {
    echo "$number is in the range of 1 to 100.";
} else {
    echo "$number is above 100.";
}
?>
```

### 6. Correct the Following Program

```php
<?php
$x = 5;
$y = 9;

if ($x >= $y) {
    echo "x is greater than or equal to y";
} else {
    echo "y is greater than x";
}
?>
```

### 7. Switch Statement for Days of the Week

```php
<?php
$day = 3; // Input day number

switch ($day) {
    case 1:
        echo "Monday";
        break;
    case 2:
        echo "Tuesday";
        break;
    case 3:
        echo "Wednesday";
        break;
    case 4:
        echo "Thursday";
        break;
    case 5:
        echo "Friday";
        break;
    case 6:
        echo "Saturday";
        break;
    case 7:
        echo "Sunday";
        break;
    default:
        echo "Invalid day number.";
}
?>
```
