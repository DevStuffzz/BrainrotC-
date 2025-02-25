
# C++ Code Slang Documentation - BrainrotC++

This documentation provides an overview of custom macros designed to replace standard C++ keywords and syntax with fun, casual "slang". These macros can make your code look more relaxed and enjoyable while preserving the full functionality of C++.

## Table of Contents
- [Raw Data Types](#raw-data-types)
- [Control Flow](#control-flow)
- [Functions & Logic](#functions--logic)
- [Keywords](#keywords)
- [Standard Library Slang](#standard-library-slang)
- [Strings & Containers](#strings--containers)
- [Classes](#classes)
- [Extras](#extras)
- [Control Flow Alternatives](#control-flow-alternatives)
- [Entry Point](#entry-point)

---

## Raw Data Types

These macros are used to replace standard C++ data types and comparisons with more casual terms.

| Slang            | C++ Equivalent |
|------------------|----------------|
| `cap`            | `false`        |
| `nocap`          | `true`         |
| `isfr`           | `==`           |
| `isnfr`          | `!=`           |
| `leftAlligator`  | `>`            |
| `rightAlligator` | `<`            |
| `less`           | `--`           |
| `more`           | `++`           |
| `digits`         | `int`          |
| `drip`           | `float`        |
| `bigNum`         | `double`       |
| `vibeCheck`      | `auto`         |

### Usage Example:
```cpp
digits myVar = 10;
if (myVar isfr 10) {
    spill and "Vibe is good!" micdrop;
}
```

---

## Control Flow

These macros replace standard flow control keywords with more casual expressions.

| Slang            | C++ Equivalent |
|------------------|----------------|
| `lowkey`         | `if`           |
| `nah`            | `else`         |
| `noCapKeepGoing` | `while`        |
| `onRepeatFr`     | `for`          |
| `breakMyHeart`   | `break`        |
| `keepItPushin`   | `continue`     |
| `plotTwist`      | `switch`       |
| `hearMeOut`      | `case`         |
| `mid`            | `default`      |

### Usage Example:
```cpp
lowkey (myVar more 5) {
    spill and "Keep pushing!" micdrop;
} nah {
    spill and "Chill, it's lowkey" micdrop;
}
```

---

## Functions & Logic

This section provides slang alternatives for function-related keywords and exception handling.

| Slang            | C++ Equivalent |
|------------------|----------------|
| `rizz`           | `void`         |
| `shootYourShot`  | `try`          |
| `scoop`          | `catch`        |
| `rageQuit`       | `throw`        |
| `sendit`         | `return`       |

### Usage Example:
```cpp
rizz shootYourShot() {
    spill and "Shoot your shot!" micdrop;
    rageQuit;
    sendit 0;
}
```

---

## Keywords

Custom keywords that offer a casual touch to standard C++ features.

| Slang        | C++ Equivalent |
|--------------|----------------|
| `forlife`    | `const`        |
| `freshDrop`  | `new`          |
| `disBish`    | `this`         |
| `bigMood`    | `super`        |

### Usage Example:
```cpp
forlife bigMood bool isFresh = disBish->freshDrop bool;
```

---

## Standard Library Slang

These macros rename common C++ standard library functions with more casual names.

| Slang           | C++ Equivalent    |
|-----------------|-------------------|
| `SlideIntoDms`  | `std::printf`     |
| `spill`         | `std::cout`       |
| `and`           | `<<`              |
| `also`          | `<<`              |
| `micdrop`       | `std::endl`       |
| `listen`        | `std::cin`        |

### Usage Example:
```cpp
SlideIntoDms("Hello World!" micdrop);
spill and "This is how we roll!" micdrop;
```

---

## Strings & Containers

These macros provide slang names for common C++ string and container types.

| Slang             | C++ Equivalent              |
|-------------------|-----------------------------|
| `word`            | `std::string`               |
| `receipts`        | `std::vector`               |
| `deepCopy`        | `std::make_shared`          |
| `sharedCustody`   | `std::shared_ptr`           |
| `weakLink`        | `std::weak_ptr`             |
| `oneAndOnly`      | `std::unique_ptr`           |
| `bringInTheHomies`| `std::make_unique`          |

### Usage Example:
```cpp
word myWord = "Hello!";
receipts<int> numbers = {1, 2, 3};
auto deepVar = deepCopy<MyClass>(myWord);
```

---

## Classes

These macros provide slang alternatives for class-related keywords.

| Slang         | C++ Equivalent   |
|---------------|------------------|
| `blueprint`   | `class`          |
| `whipUpStruct`| `struct`         |
| `getToWork`   | `public`         |
| `lowProfile`  | `private`        |
| `kindaSecret` | `protected`      |
| `gasUp`       | `friend`         |
| `realTalk`    | `virtual`        |
| `newDrip`     | `override`       |
| `oldDrip`     | `final`          |
| `blueprint`   | `abstract`       |
| `ghostMethod` | `pure`           |
| `copyMe`      | `explicit`       |
| `dontCopyMe`  | `delete`         |
| `lilHelper`   | `static`         |
| `glowUp`      | `mutable`        |
| `bop`         | `noexcept`       |

### Usage Example:
```cpp
blueprint MyClass {
    getToWork void sayHi() {
        spill and "Hello from class!" micdrop;
    }
};
```

---

## Extras

Slang for commonly used operators and expressions.

| Slang         | C++ Equivalent |
|---------------|----------------|
| `deadAnd`     | `&&`           |
| `deadOr`      | `||`           |
| `nahFam`      | `!`            |
| `vibeIs`      | `==`           |
| `vibeAint`    | `!=`           |
| `levelUp`     | `++`           |
| `levelDown`   | `--`           |
| `dropHalf`    | `/= 2`         |
| `doubleUp`    | `*= 2`         |
| `taxMe`       | `-=`           |
| `blessMe`     | `+=`           |

### Usage Example:
```cpp
vibeIs myVar more 5 levelUp;
nahFam myVar deadAnd myOtherVar vibeAint 0;
```

---

## Control Flow Alternatives

These macros offer slang alternatives for additional control flow structures.

| Slang        | C++ Equivalent |
|--------------|----------------|
| `highkey`    | `else if`      |
| `frfr`       | `return`       |
| `aightDoThis`| `do`           |
| `bet`        | `continue`     |
| `squadUp`    | `goto`         |

### Usage Example:
```cpp
highkey (myVar vibeIs 10) {
    spill and "All good!" micdrop;
} frfr {
    spill and "Catch you later!" micdrop;
}
```

---

## Entry Point

The slang version of `main()`.

| Slang         | C++ Equivalent    |
|---------------|-------------------|
| `rizzup`      | `int main`        |

### Usage Example:
```cpp
rizzup {
    spill and "Welcome to the code!" micdrop;
    frfr 0;
}
```

---

### How to Use:
To incorporate these slang macros into your code:
1. Include the header file in your project.
2. Replace standard C++ keywords with their corresponding slang macros.
3. Enjoy writing code in a more fun, casual way!

---

**Note:** While these macros make the code look more informal and entertaining, it’s important to remember that they are primarily for fun. In professional environments, you should consider using standard C++ syntax for clarity and maintainability.
