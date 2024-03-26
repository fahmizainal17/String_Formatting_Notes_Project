# String Formatting Notes Project

Welcome to the **String Formatting Notes Project**! This repository is dedicated to exploring the intricacies of string manipulation in Python, focusing primarily on two widely used techniques: the modulo operator (%) for string formatting and the more modern `format()` method. These notes aim to provide clear examples and explanations of how to effectively utilize these techniques in various scenarios.

## Using the Modulo Operator

The modulo operator `%` is one of the earliest methods introduced in Python for string formatting. It allows you to embed variables inside a string by using `%s` for strings, `%d` for integers, and `%f` for floating-point numbers, among others. Here are some examples demonstrating its usage:

### Basic String and Integer Formatting

```python
name = 'Fahmi'
age = 32
string = "Hi there!, I'm %s, I'm %d years old" % (name, age)
print(string)
# Output: Hi there!, I'm Fahmi, I'm 32 years old
```

### Multiple Substitutions

```python
x = "fahmi"
string = "Imran has friends named %s and %s" % (x, "syukri")
print(string)
# Output: Imran has friends named fahmi and syukri
```

### Formatting Floating-Point Numbers

```python
print("She has total money spent today of rm%3.2f" % (101.23))
# Output: She has total money spent today of rm101.23
```

## Using the `format()` Method

The `format()` method provides a more versatile and readable approach to string formatting. It replaces placeholders — defined by `{}` in the string — with the arguments provided to `format()`.

### Basic Usage

```python
print("Welcome to {}'s home sweet home".format("Fahmi"))
# Output: Welcome to Fahmi's home sweet home
```

### Specifying Argument Index

```python
print("Hi {1}, may I ask you something? You're friends with {0}, right?".format("Fahmi", "Mr. Syukri"))
# Output: Hi Mr. Syukri, may I ask you something? You're friends with Fahmi, right?
```

## Repository Structure

- **`.venv`**: Contains virtual environment files.
- **`string_manipulation`**: Directory with example scripts showcasing string formatting techniques.
- **`.gitignore`**: Configuration file for Git to ignore certain files and directories.
- **`LICENSE`**: The project's open-source license (MIT License).
- **`README.md`**: Provides an overview of the project and explanations of string formatting methods.

## Learning Outcomes

From this project, you should learn that:

- The modulo operator `%` is a straightforward method for substituting variables into strings by using placeholders like `%s`, `%d`, and `%f`.
- The `format()` method offers a more flexible and intuitive way to format strings, allowing for reordering and more readable code.
- Properly formatting strings is essential for creating dynamic and user-friendly output in Python applications.

## Conclusion

String formatting is a fundamental aspect of Python programming, enabling developers to generate dynamic text output. Whether you prefer the modulo operator for its simplicity or the `format()` method for its flexibility, understanding these techniques is crucial for effective Python development.

Feel free to dive into the `string_manipulation` directory for practical examples and to experiment with these concepts on your own. Happy coding!
