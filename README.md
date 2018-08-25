# Dago Hoogeschool 2018 Code Documentation

This is the central repository for documenting the code used in KRI 2018 by Dago Hoogeschool.

## How to start

First, you must install a **decent text editor** like VSCode, Atom, Sublime, or Notepad++. Please **AVOID** things like **Geany**, **WordPad**, others embedded text editor, or even **Notepad** to do the code documentation.

This guide assumes you have **basic understanding** over `C++` language and will cover how to setup VSCode to do a good documentation on the code. Please use UNIX based OS like Linux or MacOS, if you use Windows don't forget to convert the line ending from `CRLF` to `LF` in the text editor.

## Our Code Conventions

This documentation will follow the code conventions from [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html#Line_Length) with some adaptation. If you have time please read that style guide first :)).

In short, here are the following guides that must be used :

* Each line in code must not exceed **120 characters** (Tentative).

* Please use **2 spaces** to indent the code. **NOT** using **TABS**.

* No **trailing whitespaces** on end of the line or blank line of code.

* Use **one indent** on public, private, or protected block.

* Use meaningful and relevant **variable** or **method name** :D (Tentative).

* Use `foo = int(bar)` instead of `foo = (int)bar` to convert the RHS type into Integer,

* Always put newline at the **End of File** (EOF).

* All block of code will look like this.

  * For class declaration

  ```c++
    Class Foo {
      public:
        Foo();

      private:
        int SumOfTwoInt(int a, int b);
    }l;
  ```

  * For conditional

  ```c++
    if (something) {

    } else {

    }

    switch (var) {
      case 0: {
        ...
        break;
      }
      default: {
        ...
      }
    }
  ```

## How to Setup Text Editor

### VSCode

For you who already use VSCode then this text editor already using **spaces** instead of tabs to indent the code.

But you must still configure how much spaces used to indent the code by putting this line in `User Settings` in VSCode. To Access `User Settings` you can use `Ctrl+,` or go to Tab `File > Preferences > Settings`. Also set the auto indent to `true` in the settings.

```json
  "editor.tabSize": 2,
  "editor.autoIndent": true
```

Don't forget to change the word wrap settings to in VSCode to see if the code is exceeding the maximum line length.

```json
  "editor.wordWrap": "wordWrapColumn",
  "editor.wordWrapColumn": 120
```

Enable the `Render Whitespace` feature in the VSCode to see any trailing whitespace on any line of code. To enable the `Render Whitespace` you can go to `View > Toggle Render Whitespace`.

Enable settings in VSCode to insert the newline at the End of File (**EOF**) when saving file with

```json
  "files.insertFinalNewline": true
```

Any editor settings that don't related to the documentation can be edited to make yourself comfortable to do the coding :).

## Doxygen Guide

TBD

## Contribution Guide

1. If you don't have access to this repo, please contact Hisham to grant you access to this repository.

2. Please use `git add <filename1> <filename2>` instead of `git add .` to add your changes to Git.

3. Please use meaningful and relevant commits message when you commit your changes on this repo.

4. You can learn basic of Git from [Atlassian](https://www.atlassian.com/git). For further assistance on Git you can contact members of programming division to help you.

5. Thank You! Your Contributions Did Matter!

## Help

If you need help or find some issue related to this documentation, you can contact Hisham Lazuardi or Salman Al Farisi directly.
