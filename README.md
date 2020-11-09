
#include <iostream>
#include <algorithm>

int main()
{
    int list[4] = {10, 40, 7, 8};
    std::cout << *std::max_element(list, list+4);

   return 0;
}
