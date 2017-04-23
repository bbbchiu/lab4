for question a:
	the nm shows:
		0000000000000068 T main
		0000000000000040 T _Z7averageif
		0000000000000000 T _Z7averagePdRd
	the compiler used function_name_length, function_name, input_types

for question b:
	output:
		1 8
		4 8
		4 8
		8 8
	reason:
		the pointer is 8 bytes, while the char is one byte,
		the int and the float is 4 bytes, and the double is 8 bytes.
