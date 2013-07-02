JPEG-optimization
=================

Batch Processing your JPEGs with jpegtran


How to use this script

For starters, copy this script into a text file (such as optimize_jpegs.pl) and set it to be executable (chmod 755 optimize_jpegs.pl).

After the script is setup, pull the trigger…

$ ./optimize_jpegs.pl  /path/to/your/images/dir

That’s it.  The output should look something like this:

Inspecting ./phpXkWlcW.jpg
 -- Progressive JPEG optimization: saved 1089 bytes (orig 13464)
Inspecting ./phpCnBRri.jpg
 -- Progressive JPEG optimization: saved 1155 bytes (orig 34790)
Inspecting ./phpx6G3lD.jpg
 -- Progressive JPEG optimization: saved 742 bytes (orig 11493)

...

----------------------------
  Sumary
----------------------------

  Inspected 21 JPEG files.
  Modified 21 files.
  Huffman table optimizations: 0
  Progressive JPEG optimizations: 21
  Total bytes saved: 63918
