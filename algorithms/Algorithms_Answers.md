Add your answers to the Algorithms exercises here.

I)
    a) This loop will run until a * n * n is equal to n, which will require n times. O(n)

    b) Three loops run dependant on the length of n. O(n^3)

    c) It will run until bunnies reaches 0 with 1 bunny removed at a time in a linear fashion. O(n)

II)
    Since it either breaks from a floor or it doesn't I would use a binary search approach. If it breaks: cut my floor number in half and test again until I get the right floor. If it doesn't break: Double my floor number and test again until I get the right floor. This should find the floor in O(log n) time.