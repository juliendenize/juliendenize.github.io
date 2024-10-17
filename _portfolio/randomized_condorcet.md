---
title: "Randomized Condorcet"
collection: portfolio
permalink: /portfolio/job_reco
date: 2018-04-01
excerpt: 'Java; PHP; Bootstrap 3<br/>[Github](https://github.com/juliendenize/Randomized_Condorcet/tree/master/Java/Algortihme%20de%20Condorcet/src/main)'
---

## About
The aim of our project is to provide a web platform enabling users to create and vote for randomized Condorcet ballots.

These ballots consist of following Condorcet's method, which ranks each of the choices in the ballot according to the preference of the voters, or not ranking them at all. Each choice is then “matched” to the others one by one, so that for each relationship between the votes, there is a winner of the “match”. This allows us to elect the Condorcet winners, who are, if they exist, those who have won each of their matches. In the event that no winner is designated (Condorcet paradox), the winner is chosen according to a probability law from among the candidates at the top of the voting.

For our web platform, we have decided to provide two types of vote: private and public. For private voting, the vote administrator can define in advance the set of people authorized to vote. Voters must have an account on the site in order to test their ability to access votes. No account is required for public voting, which is open to anyone.

As far as voting procedures are concerned, the voter ranks the various alternatives he or she considers relevant. The method remains to be defined: dragging the alternatives into the desired positions or sectioning them from a drop-down option choice for each position.

From the administrator's point of view, the voting process consists of defining the object of the vote, the different choices, and the exact date for closing the vote. He obtains the final result of the vote at the end of this date. From the user's point of view, the voting process consists of accessing the system via a link or by browsing the votes available to him (public or private), then voting according to his preferences. Finally, securing votes is a key point in our project, but our lack of knowledge in this area means that we need to find out more before following a security strategy.


## Code Link

[Github](https://github.com/juliendenize/Randomized_Condorcet/tree/master/Java/Algortihme%20de%20Condorcet/src/main)

## Stack

Java; PHP; Bootstrap 3
