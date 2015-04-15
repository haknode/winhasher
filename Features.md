# Features #

  * Two primary interfaces: A small Windows GUI applet and a console (command line) program
  * Three primary operating modes: Compute the hash of a single file, compare the contents of multiple files by comparing the hash of each one, or hash arbitrary text
  * Supported hashing algorithms: [MD5](http://en.wikipedia.org/wiki/MD5), [SHA-1](http://en.wikipedia.org/wiki/SHA_hash_functions), SHA-256, SHA-384, SHA-512, [RIPEMD-160](http://en.wikipedia.org/wiki/RIPEMD), [Whirlpool](http://en.wikipedia.org/wiki/Whirlpool_%28cryptography%29) (2003 revision), and [Tiger](http://en.wikipedia.org/wiki/Tiger_%28hash%29) (1995 original, not "Tiger2")
  * Supported output formats: [Hexadecimal](http://en.wikipedia.org/wiki/Hexadecimal) (with either lower-case or upper-case letters), [Base64](http://en.wikipedia.org/wiki/Base64), [Bubble Babble](http://en.wikipedia.org/wiki/Bubble_Babble)
  * Windows applet supports drag-and-drop functionality; automatically compute the hash of a single file by dropping it onto the applet, or drop one or more files to add them to the compare list
  * Optional "Send To" shortcuts allow you to right-click any file in Windows Explorer and instantly get its hash, or right-click multiple files to compare their contents
  * Long running processes (such as hashing an individual very large file or comparing the hashes of many files) can now be cancelled when running in GUI mode
  * Remembers last used settings such as hash algorithm, output format, last folder/directory, mode tab, etc.
  * Can hash a total amount of data in one process up to 8.05EB (exabytes)!