# InterviewQuestionInKotin
swap these  number |swap  two number without using a temporary variable | Is number even or odd ?
##  1. You have two number x=10, y=20 you need to swap these two number the output x=20, y=10
``` kotlin
private fun swapNum() {
        var x = 10
        var y = 20
        println("value before change :: x = $x :: y= $y")
        val temp: Int
        temp = x;
        x = y
        y = temp

        println("value after change :: x = $x :: y= $y")
    }
```
##  2. You have two number x=10, y=20 you need to swap these two number without using a temporary variable
```kotlin
 private fun swapNumWithoutTemp() {
        var x = 10
        var y = 20
        println("value before change :: x = $x :: y= $y")
        x = x + y //30
        y = x - y //30-20=10
         x = x - y
        println("value after change :: x = $x :: y= $y")

    }
`
## Is number even or odd ?
```kotlin
private fun checkEvenOdd(num: Int) {
        if (num % 2 == 0) println("No is Even")
        else println("No is Odd")
    }
```
