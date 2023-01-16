# How to search for specific words in files in the Linux Command Line

### We use the command `grep` to find files or folders in Linux

- To find a specific word in specific files (Case Insensitive):

  Note - You can find this specific word in as many files as you want, so please note that instead of just typing two files, type as many as you want

  ```
   $ grep -i <word-you-want-to-find> <file-you-will-search-in> <file-you-will-search-in->
  ```

  Example: I want to find where the word `three` is in the file three/three.txt Three/Three.txt and THREE/THREE.txt case insensitive

  ```
  grep -i three three/three.txt Three/Three.txt THREE/THREE.txt
  ```

- To find a specific word in specific files (Case Sensitive):

  Note - You can find this specific word in as many files as you want, so please note that instead of just typing two files, type as many as you want

  ```
   $ grep <word-you-want-to-find> <file-you-will-search-in> <file-you-will-search-in->
  ```

  Example: I want to find where the word `three` is in the file three/three.txt Three/Three.txt THREE/THREE.txt case sensitive

  ```
  grep -i three three/three.txt THREE/THREE.txt Three/Three.txt
  ```

- To find a specific word recursively, searching in all files in the current directory (Case Insensitive):

  ```
  $ grep -ri <word-you-want-to-find> *
  ```

  Example: I want to find all the files that have `four` in them case insensitive

  ```
  grep -ri four *
  ```

  Or, if I want to find all the files that have the extension .txt, and the content is `one` case insensitive:

  ```
  grep -ri --include="*.txt" one
  ```

- To find a specific word recursively, searching in all files in the current directory (Case Sensitive):

  ```
  $ grep -r <word-you-want-to-find> *
  ```

  Example: I want to find all the files that have `four` in them case sensitive

  ```
  grep -r four *
  ```

  Or, if I want to find all the files that have the extension .txt, and the content is `two` case sensitive:

  ```
  grep -r --include="*.txt" two
  ```
