# asyncollective C and C++ Manual of Style
This document intends to provide guidelines for asyncollective members and project contributors who write C and C++ code.

## Code formatting
* When declaring a pointer, place the asterisk (*) next to the type name (ex. `char* example = "Hello";`)
* Modifiable values are declared with an ampersand (&) placed before the identifier (ex. `void AddNumbersToBuffer(int a, int b, int &buf);`
* Brackets which enclose multiple lines are fully spaced out, like in this example:
```
bool IsFunky(std::string input)
{
    if (input == L"funky")
    {
        return true;
    }
    else
    {
        return false;
    }
}
```
