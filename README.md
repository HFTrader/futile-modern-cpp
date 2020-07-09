# futile-modern-cpp
List of futile Modern C++ projects, written either for fun or just because. 
This is not a place for bad design or bad implementations or decisions, just a place for projects written just because "Modern C++".

## Contributing 

To add, remove or change things on the list:
[please submit a pull request to the GitHub repository](https://github.com/HFTrader/futile-modern-cpp).



## General/Unclassified

- [Single Producer, Single Consumer (and Single Thread!) Queue](https://github.com/SteveZhangSZ/ConstexprCircularQueue). 

The problem here is not the project itself but the lack of usefulness. 80% of the code deals with move semantics. However, this queue cannot be used for multi-threading communication. If not used for threads, why would someone possibly use a circular queue when the standard library provides std::queue that's way more flexible?

- [String Split Saga](https://brevzin.github.io/c++/2020/07/06/split-view/) continued. How NOT to split a string, C++ style. 


