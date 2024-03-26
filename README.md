Use the bash file to prompt the directory to encrpit and the seed to use for the encripion (to ensure the encritpion key is unique the filename is concatenated to the seed).
The bash script will run the .C file for each file in the directory and subdirectories. 
For safety the encritpted contents will be written to another file named <filename>.encripted instead of overwritting on the originals (you can very easily change this =) )
