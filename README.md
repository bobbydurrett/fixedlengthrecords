# fixedlengthrecords
Python implementation of Rosetta Code task "Fixed length records"

http://rosettacode.org/wiki/Fixed_length_records

dd if=sample.txt of=infile.dat cbs=80 conv=block
0+1 records in
1+1 records out
2 truncated records

dd if=infile.dat cbs=80 conv=unblock > out.txt
1+1 records in
0+1 records out

