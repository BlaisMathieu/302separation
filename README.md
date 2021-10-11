# 302separation
Epitech 3rd year maths project


In 1929, a Hungarian named Frigyes Karinthy established the theory of six degrees of separation: every person in the world can be connected to any other person via a chain of individual relationships, that has no
more than six links. Nowadays, social networks makes it easy to evaluate the degree of separation between
two individuals, and to test this theory.
Starting with a file that contains a list of friendship links between different Facebook accounts, the goal of
this project is to use graph theory to compute the degree of separation between two people.
Your program must display the following:
• the list of people in alphabetical order (the order that will be used to build the matrices),
• the adjacency matrix,
• the matrix of the shortest paths, with lengths less than or equal to n.
If two names are given as argument to the program, it must instead display the degree of separation between those two people, or -1 if they are not connected.
Friendships are reciprocal in Facebook: if A is friends with B, B is also friends with A

USAGE:
./302separation file [n | p1 p2]
DESCRIPTION
file file that contains the list of Facebook connections
n maximum length of the paths
pi name of someone in the file

EXAMPLE:
./302separation example “Yvette Horner” “Barack Obama”
or
./302separation example 3
