A simple and efficient number formatting utility for Java applications. This project provides methods to format numbers into human-readable strings, such as converting large numbers into abbreviated formats (e.g., 1,000,000 to 1M).

# Features

Convert large numbers to readable formats (e.g., K, M, B, T suffixes)

Easy-to-use API

Lightweight and efficient

# Usage

```java
public class Main {
    public static void main(String[] args) {
        System.out.println(NumFormatter.format(1000));       // Output: 1K
        System.out.println(NumFormatter.format(10000));      // Output: 10K
        System.out.println(NumFormatter.format(100000));     // Output: 100K
        System.out.println(NumFormatter.format(1050));       // Output: 1.05K
        System.out.println(NumFormatter.format(10100));      // Output: 10.1K
    }
}
```

# Contributing

Contributions are welcome! Feel free to fork the repo, make changes, and submit a pull request.

# License

This project is licensed under the MIT License - see the LICENSE file for details.

# Contact

For any questions or suggestions, reach out to me on Discord at 'aquatikss'.

