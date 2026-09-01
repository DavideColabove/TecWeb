# Description

A.A. 2021-22 - PHP part 3

## Array's functions

PHP allows us to perform many actions on an array

![separation_principle](../assets/array_functions.png)

### Array-specific cycles

This syntax is designed to print an array:

![separation_principle](../assets/array_cicle.png)

And this is for editing it too:

![separation_principle](../assets/editing_array.png)

For associative arrays we can only edit the value but not the key

## Functions

Functions are defined using the function keyword and parameters are passed as value:

![separation_principle](../assets/funciton_example.png)

We can also pass them as a reference using &

## Variables scope

The default variable scope is the PHP script itself, but global variables are not visible inside funcitons if  they aren't defined as explicit global

![separation_principle](../assets/variable_scope.png)

in this case we should decalre global $a, $b

## Superglobal variables

These variables are accessible everywhere:

![separation_principle](../assets/superglobal_varaibles.png)


## Returning query results

The query result can be very big in terms of bytes, for scalability reasons it is necessary to bufferize the result on the client-side in order to be able to navigate throught it.

The query() function occupies both of executing a query and then bufferizing the result.

![separation_principle](../assets/query_execution.png)

And here how you can cycle the returned results:

![separation_principle](../assets/cycle_records.png)

## Setting up characters set

![separation_principle](../assets/charset.png)

