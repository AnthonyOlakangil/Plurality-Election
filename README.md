- A plurality election simply means a voter can vote for one person, and the candidate with the most votes wins the election.
- A runoff election entails the voter ranking all of the candidates, not just one, with 1 being their top choice. Consider the following 9 ballots:

Ballot    

   Voter 1    Voter 2     Voter 3     Voter 4     Voter 5     Voter 6     Voter 7     Voter 8     Voter 9
1. Alice    | Alice     | Bob       | Bob       | Bob       | Charlie   | Charlie   | Charlie   | Charlie
2. Bob      | Bob       | Alice     | Alice     | Alice     | Alice     | Alice     | Bob       | Bob
3. Charlie  | Charlie   | Charlie   | Charlie   | Charlie   | Bob       | Bob       | Alice     | Alice

In this scenario of 9 ballots and 3 candidates, Alice appears as a first choice the least times (2) so she is eliminated. Out of the two ballots 
where Alice was once considered as a first choice, Bob is the second highest preference and takes her place. Now, Bob holds 2 + 3 = 5 votes and Charlie holds 4.
Bob is the winner. Runoffs are considered more advanced than plurality and better voice the voters' preferences.


- Uses cs50 library and string library
- Same compilation process for both programs
- Usage: plurality [candidate ...] where [candidate ...] are the command line arguments (user-inputted candidates)
- i.e. ./plurality John Carl Bob
- in order to compile, download cs50.h header file and cs50.c source code and include in the directory then type the following into the terminal

- gcc ./plurality.c cs50.c
- mv a.exe plurality.exe
- ./plurality [candidate ...]



