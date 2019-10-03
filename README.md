# fixedlengthrecords
Python implementation of Rosetta Code task "Fixed length records"

http://rosettacode.org/wiki/Fixed_length_records

dd if=sample.txt of=infile.dat cbs=80 conv=block
0+1 records in
1+1 records out
2 truncated records

dd if=infile.dat cbs=80 conv=unblock
Line 1...1.........2.........3.........4.........5.........6.........7.........8
Line 2
Line 3
Line 4

Line 6
Line 7
     Indented line 8............................................................
Line 9                                                                 RT MARGIN
1+1 records in
0+1 records out

dd if=outfile.dat cbs=80 conv=unblock
8.........7.........6.........5.........4.........3.........2.........1...1 eniL
2 eniL
3 eniL
4 eniL

6 eniL
7 eniL
............................................................8 enil detnednI
NIGRAM TR                                                                 9 eniL
1+1 records in
1+1 records out

C:\Users\p1c1227\OneDrive - US Foods\todoitems\rosettacode\fixedlengthrecords>