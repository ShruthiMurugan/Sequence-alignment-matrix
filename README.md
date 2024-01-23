->Key Features:

1.Dynamic programming approach is used

2.Generates an alignment matrix showing the  Longest Common Subsequence (LCS) at every position.

3.Can be adapted for different scoring schemes and gap penalties

->Populating alignment matrix using following parameters:

   Match score=+2
   
   Mismatch score=-1
   
sequence 1=['A','C','A','C','A','C','T','A','T','C','G','A']

sequence 2=['A','G','C','A','C','A','C','A','G','C','T','A']

->Output:

1.The script prints the alignment matrix.

2.You can trace back the highest values in the matrix to reconstruct the LCS.
