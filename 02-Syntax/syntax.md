# C++ Syntax

Let's break down the following C++ code to understand it better.

## Example

```cpp
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World!";
  return 0;
}
```

---

# Example Explained

## Line 1

```cpp
#include <iostream>
```

`#include <iostream>` is a header file library that allows us to work with input and output objects such as `cout`.

Header files add extra functionality to C++ programs.

---

## Line 2

```cpp
using namespace std;
```

This means we can use names for objects and variables from the standard library without writing `std::`.

Example:

```cpp
cout << "Hello";
```

instead of:

```cpp
std::cout << "Hello";
```

---

## Line 3

A blank line.

C++ ignores white spaces, but we use them to make code more readable.

---

## Line 4

```cpp
int main() {
```

`main()` is a function.

Every C++ program must have a `main()` function because program execution starts from here.

Any code inside `{ }` will be executed.

---

## Line 5

```cpp
cout << "Hello World!";
```

`cout` (pronounced **see-out**) is used to display output on the screen.

The `<<` operator is called the **insertion operator**.

Output:

```text
Hello World!
```

### Note

C++ is **case-sensitive**:

```cpp
cout
```

and

```cpp
Cout
```

are different.

---

## Semicolon (;)

Every C++ statement ends with a semicolon `;`.

Example:

```cpp
return 0;
```

---

## One-Line Version

The program can also be written like this:

```cpp
int main() { cout << "Hello World!"; return 0; }
```

However, writing code on multiple lines improves readability.

---

## Line 6

```cpp
return 0;
```

This ends the `main()` function.

`0` usually means the program executed successfully.

---

## Line 7

```cpp
}
```

This closing curly bracket ends the `main()` function.

Do not forget it.

---

# Important Points

- C++ ignores extra spaces and blank lines
- Every statement ends with `;`
- `main()` is required in every C++ program
- `cout` is used for output
- C++ is case-sensitive