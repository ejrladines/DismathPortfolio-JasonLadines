# DismathPortfolio-JasonLadines

##Week 1 (June 9,2016)
On our first day of meeting, we were oriented about the course Discrete Mathematics. We also started with the first topic which is the proposition. A proposition is a declarative statement that is either true or false.

For our first exercise, each of us were given a question to be answered. The question that was asked to me was how to make the statement "x+9=11" a proposition. That statement is not a proposition since it can be true or false depending on the value of x. I was able to answer the questions by adding "...if x=2" to the statement. The statement "x+9=11 if x=2" is now a proposition since the statement becomes true.

We ended our first day of meeting with choosing a time and day schedule for our classes.

##(June 14, 2016)
LEAP Day (No Classes)

##Week 2 (June 16, 2016)
Our next meeting was the start of our official lesson. On this day, we discussed more about propositions. This included the different operations that can be used with the propositional variables. The following are the operations that can be used on propositional variables:

| Operation             | Logical Equivalent | Symbol | Definition                                       |
|-----------------------|--------------------|--------|--------------------------------------------------|
| Negation              | NOT                | ¬      | If p is T, ¬p is F                               |
| Conjunction           | AND                | ∧      | p ∧ q is T if p and Q is T                       |
| Disjunction           | OR                 | ∨      | p ∨ q is T if any of p or q or both is T         |
| Exclusive Disjunction | XOR                | ⊕      | p ⊕ q is only one of p or q is T                 |
| Conditional           |                    | →      | p → q is F if p is T and q is F                  |
| Biconditional         |                    | ↔      | p ↔ q is T if p and q have the same truth values |

In addition to these operations that can be used on propositions, we were also taught about the other forms that is related to conditional statements. These are:

| Operation      | Expression |
|----------------|------------|
| Converse       | q → p        |
| Contrapositive | ¬q → ¬p      |
| Inverse        | ¬p → ¬q      |

As a closing remarks for the first chapter of the book, some of us were asked some questions. I was asked the question, "What is the Bitwise OR of 01 and 11?" I was able to answer the question in which the answer is 10.

To test if we learned from the class today, each and every on of us answered some questions from the Chapter 1 Questions found in the book. The questions that I was able to asnwer are:

8.) Let p and q be the propositions:
p: I bought a lottery ticket this week.
q: I won the million dollar jackpot.
Express each of these propositions as an English sentence.
d.) p ∧ q
Answer: I bought a lottery ticket this week and won the million dollar jackpot.

11.) Let p and q be the propositions:
p: It is below freezing.
q: It is snowing
Write these propositions using p and q and logical connectives (including negotations).
c.) It is not below freezing and it is not snowing.
Answer: ¬p ∧ ¬q

13.) Let p and q be the propositions:
p: You drive over 65 milers per hour.
q: You get a speeding ticket.
Write these propositions using p and q and logical connectives (including negotations).
b.) You drive over 65 miles per hour, but you do not get a speeding ticket.
Answer: p ∧ ¬q

15.) Let p, q, and r be the propositions:
p: Grizzly bears hae been seen in the area.
q: Hiking is safe on the trail.
r: Berries are ripe along the trail.
b.) Grizzly bears have not been seen in the area and hiking on the trail is safe, but berries are ripe along the trail.
Answer: ¬p ∧ q ∧ r 
f.) Hiking is not safe on the trail whenever grizzly bears have been seen in the area and berries are ripe along the trail.
Answer: (p ∧ r) → ¬q

17.) Determine whether each of these conditional statements is true or false.
c.) If 1 + 1 = 3, then 2 + 2 = 5.
Answer: True

19.) For each of these sentences, determine whether an inclusive or. or an exclusive or, is intended. Explain your answer.
d.) You can pay using U.S. dollars or euros.
Answer: Either, since it depends on the rules in each country.

21.) For each of these sentences, state what the sentence means if the logical connective or is an inclusive or (that is, a disjunction) versus an exclusive or. Which of these meaning of or do you think is intended.
a.) To take discrete mathematics, you must have taken calculus or a course in computer science.
Answer: Inclusive-OR

25.) Write each of these propositions in the form "p if and only if q" in English.
c.) You get promoted only if you have connections, and you have connections only if you get promoted.
Answer: You get promoted if and only if you have connections.

29.) How many rows appear in a truth table for each of these compound propositions?
b.) (p ∨ ¬r) ∧ (q ∨ ¬s)

##Assigment No. 1:

31.) Construct a truth table for each of these compound propositions.
d.) p ∨ q) → (p ∧ q)  

| p | q | p ∨ q |  p ∧ q  | (p ∨ q) → (p ∧ q)  |
|---|---|-------|---------|--------------------|
| T | T | T     | T       | T                  |
| T | F | T     | F       | F                  |
| F | T | T     | F       | F                  |
| F | F | F     | F       | T                  |

33.) Construct a truth table for each of these compound propositions.
e.) (p ↔ q) ⊕ (¬p ↔ ¬r)

| p | q | r | ¬p | ¬r | p ↔ q | ¬p ↔ ¬r | (p ↔ q) ⊕ (¬p ↔ ¬r) |
|---|---|---|----|----|-------|---------|---------------------|
| T | T | T | F  | F  | T     | T       | F                   |
| T | T | F | F  | T  | T     | F       | T                   |
| T | F | T | F  | F  | F     | T       | T                   |
| T | F | F | F  | T  | F     | F       | F                   |
| F | T | T | T  | F  | F     | F       | F                   |
| F | T | F | T  | T  | F     | T       | T                   |
| F | F | T | T  | F  | T     | F       | T                   |
| F | F | F | T  | T  | T     | T       | F                   |

35.) Construct a truth table for each of these compound propositions.
f.) (¬p ↔ ¬q) ↔ (p ↔ q)

| p | q | ¬p | ¬q | ¬p ↔ ¬q | p ↔ q | (¬p ↔ ¬q) ↔ (p ↔ q) |
|---|---|----|----|---------|-------|---------------------|
| T | T | F  | F  | T       | T     | T                   |
| T | F | F  | T  | F       | F     | T                   |
| F | T | T  | F  | F       | F     | T                   |
| F | F | T  | T  | T       | T     | T                   |
