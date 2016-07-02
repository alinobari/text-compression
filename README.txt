-Only works with a .txt file
-The original textfile will be compressed to a .mtf file

To Compress/Encrypt (Windows Command Line)

	->python ./mtfencode.py [textfile]

To Decompress/Decrypt 

	->python ./mtfdecode.py [textfile]

Encryption example

	->python ./mtfencode.py ./testfiles/hello.txt

		-the file will then be converted to hello.mtf
		-must run mtfdecode.py to decode file