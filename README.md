# cityflow

### Dataset retired from Aveiro Tech City Living Lab

The code starts a spark session to read the file containing several json objects.

Them, we cast the "acceleration" column as a double value, order it and get the first value to get the max acceleration in the dataset.

After that we select the specific entityId to check the historic of the car position, acceleration and velocity.

The last line we check the speed greatest speed using the same method as the acceleration.
