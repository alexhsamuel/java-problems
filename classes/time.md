1. Write an interface called `Time`, which has two getters, one for the hour (between 0 and 23) and one for the minute (between 0 and 59).

1. Write a class `Clock` that implements `Time`.

1. Write another interface for setting the clock, called `ClockSet`. It only has one method, which takes both the hour and the minute as arguments. Make the class implement this interface.

1. Write a third interface that extends `Time`, called `AccurateTime`.  (An interface can extend another interface.)  It has a third getter for the seconds (between 0 and 59).

1. Write another class that implements `AccurateTime`, called `AccurateClock`.

1. For each class, include a `toString()` method that prints the time. Write a few tests to make sure the code works.
