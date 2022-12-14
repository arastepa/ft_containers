# ft_containers
The standard C++ containers have all a specific usage.
To make sure you understand them, let’s re-implement them!

##### Mandatory part
Implement the following containers and turn in the necessary <container>.hpp files:
- vector
You don’t have to do the vector bool specialization.
- map
- stack
It will use your vector class as default underlying container. But it must still be
compatible with other containers, the STL ones included.
You can pass this assignment without the stack (80/100).
But if you want to do the bonus part, you have to implement the 3
mandatory containers: vector, map and stack.
You also have to implement:
- iterators_traits
- reverse_iterator
- enable_if
Yes, it is C++11 but you will be able to implement it in a C++98 manner.
This is asked so you can discover SFINAE.
- is_integral
- equal and/or lexicographical_compare
- std::pair
- std::make_pair
##### Requirements
- The namespace must be ft.
- Each inner data structure used in your containers must be logical and justified (this
means using a simple array for map is not ok).
- You cannot implement more public functions than the ones offered in the standard
containers. Everything else must be private or protected. Each public function or
variable must be justified.
- All the member functions, non-member functions and overloads of the standard
containers are expected.
- You must follow the original naming. Take care of details.
- If the container has an iterator system, you must implement it.
- You must use std::allocator.
- For non-member overloads, the keyword friend is allowed. Each use of friend
must be justified and will be checked during evaluation.
- Of course, for the implementation of map::value_compare, the keyword friend is
allowed.
You can use https://www.cplusplus.com/
and https://cppreference.com/ as references.
##### Bonus part
You will get extra points if you implement one last container:
- set
But this time, a Red-Black tree is mandatory.
The bonus part will only be assessed if the mandatory part is
PERFECT. Perfect means the mandatory part has been integrally done
and works without malfunctioning. If you have not passed ALL the
mandatory requirements, your bonus part will not be evaluated at all.
