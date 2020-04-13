# Encrytion-Decryption

This command line program takes in data as either a file or a string and writes the encrypted or decrypted data
 to a file or the command line. There are two encryption algorithms. "unicode" shifts all characters
 by the designated key, and "shift" only shifts english letters.
 
 
 Command line arguments:
 
       -mode   "enc" for encrypt or "dec" for decrypt
       
       -data   the string to be encrypted or decrypted
       
       -alg    selects algorithm. Either "shift" or "unicode"
       
       -in     the file to be encrypted or decrypted
       
       -out    the file to write the results too
       
       -key    integer value that determines how for charachters ore shifted


 If an input file and string are both given, the string will be processed and the file will be ignored.
 If no output file in given, output will be written to the command line.
 Arguments can be given in any order.


 Example input: java Main -mode enc -key 5 -data "Hello world!" -alg unicode
 
 Example Output: Mjqqt%|twqi&
