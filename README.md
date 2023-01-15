# How to search in the Linux Command Line

### We use the command `find` to find files or folders in Linux

- To find all the files (Case Insensitive):

  ```
  $ find <folder-you-want-to-search-in> -iname <file-name> -type f
  ```

  Example: I want to find all the files that have `three` in their name case insensitive

  ```
  find . -iname three.txt -type f
  ```

- To find all the files (Case Sensitive):

  ```
  $ find <folder-you-want-to-search-in> -name <file-name> -type f
  ```

  Example: I want to find all the files that have `two` in their name case sensitive

  ```
  find . -name two.txt -type f
  ```

- To find all the folders (Case Insensitive):

  ```
  $ find <folder-you-want-to-search-in> -iname <folder-name> -type d
  ```

  Example: I want to find all the folders that have `four` in their name case insensitive

  ```
  find . -iname four -type d
  ```

- To find all the folders (Case Sensitive):

  ```
  $ find <folder-you-want-to-search-in> -name <folder-name> -type d
  ```

  Example: I want to find all the folders that have `five` in their name case sensitive

  ```
  find . -name five -type d
  ```
