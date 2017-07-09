# numpy2stl - numpy to C++ STL

When I create new algorithms or if I need to rewrite an existing algorithm in C++, I always create a prototype using Python/ numpy/scipy, so that I can test the algorithm efficiently. I then convert this Python implementation to C++ STL. In doing so, I consult this list [numpy2stl](https://github.com/zenr/numpy2stl/blob/master/numpy2stl). 

For example as shown in the first example, if you need to find if there is atleast one element that satisfies a given condition, you can use np.any() function in numpy and for the C++ version, use find_if().



