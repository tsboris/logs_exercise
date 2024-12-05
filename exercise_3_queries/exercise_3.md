# Elastic Stack Exercise 3 - Treasure Hunt
In this exercise, we will be using the logs from the previous exercise and we will be using Kibana to find the treasure.

## How to
Participants will run a series of queries to uncover specific words hidden in the log data. Each query will reveal a word, and all the words together will form a sentence.

The Sentences is comprised of 5 words.
*Clue: the first letters of each word are: `LNL,UD`*

For each word, there is a clue/instruction. You will need to create a query to find the word based on the clue.
For all of the words, execpt one, the query should return a single log line.

## Word no. 1
Instructions:
*Find requests coming from the IP address 192.168.1.1 that are accessing a path starting with the letters lo.*

## Word no. 2
Instructions:
*Find requests that resulted in a redirection and originated from a page titled after a famous 80s song about never giving up.*
Clue: Never gonna give you up, Rick Astley

## Word no. 3
Instructions:
*Look for requests to a path associated with truth, but they came from an agent of dishonesty.*

## Word no. 4
Instructions:
*Find critical logs where the description mentions an invalid header sent upstream and originates from a client close to home*
Clue: Rearrange the results table to use custom columns (including message and ip)

## Word no. 5
Instructions:
*First responders description begins by attributing humans, and references both connections and limits. Pay attention to logs that occur at a moment often considered lucky.*

