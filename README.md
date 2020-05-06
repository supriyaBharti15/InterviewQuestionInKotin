# InterviewQuestionInKotin
swap these  number |swap  two number without using a temporary variable
##  You have two number x=10, y=20 you need to swap these two number the output x=20, y=10
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
##  You have two number x=10, y=20 you need to swap these two number without using a temporary variable
