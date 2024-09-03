# `UnluUyumuSorgula` Class

The `UnluUyumuSorgula` class is designed to analyze vowel harmony in the Turkish language. It checks various rules of vowel harmony and outputs the results.

## Features

- **Automatic Initialization:** The class automatically checks the word's eligibility for vowel harmony analysis upon instantiation.
- **Comprehensive Rule Checking:** The class provides methods to verify compliance with major and minor vowel harmony rules, considering both thickness and roundness.

## Methods

- `__init__(self, kelime)`: Initializes the class and begins the vowel harmony analysis on the given word (`kelime`).
- `UyumIncelenimiSorgula(self, kelime)`: Determines if the given word can be analyzed for vowel harmony.
- `BuyukUnluUyumuKalinlikItibariyleKontrolu(self, kelime)`: Checks if the word follows the major vowel harmony rule in terms of thickness.
- `BuyukUnluUyumuIncelikItibariyleKontrolu(self, kelime)`: Checks if the word follows the major vowel harmony rule in terms of thinness.
- `BuyukUnluUyumuKontrolu(self, kelime)`: Checks if the word follows the general major vowel harmony rule.
- `KucukUnluUyumuDuzlukItibariyleKontrolu(self, kelime)`: Checks if the word follows the minor vowel harmony rule in terms of flatness.
- `KucukUnluUyumuYuvarlaklikItibariyleKontrolu1(self, kelime)`: Checks if the word follows the minor vowel harmony rule in terms of roundness (method 1).
- `KucukUnluUyumuYuvarlaklikItibariyleKontrolu2(self, kelime)`: Checks if the word follows the minor vowel harmony rule in terms of roundness (method 2).

## Example Usage

Here is an example of how to use the `UnluUyumuSorgula` class to analyze vowel harmony in a Turkish word:

```python
ornek = UnluUyumuSorgula("hakkı")
```

## Installation

To include this class in your project, simply clone the repository and import the class into your Python project.

## License

This project is licensed under the T1 License. To obtain the license or for more information, please contact me directly. If I am not reachable, it should be considered that no license has been granted.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create a pull request or open an issue.
