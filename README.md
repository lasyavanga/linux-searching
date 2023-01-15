# How to search in the Linux Command Line

### We use the command `find` to find files or folders in Linux
- To find all the files (Case Insensitive):
    ```
    $ find <folder-you-want-to-search-in> -iname <file-name> -type f
    ```
- To find all the files (Case Sensitive):
    ```
    $ find <folder-you-want-to-search-in> -name <file-name> -type f
    ```
- To find all the folders (Case Insensitive):
    ```
    $ find <folder-you-want-to-search-in> -iname <folder-name> -type d
    ```
- To find all the folders (Case Sensitive):
    ```
    $ find <folder-you-want-to-search-in> -name <folder-name> -type d
    ```
