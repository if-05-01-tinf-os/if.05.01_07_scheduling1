### if.05.01 TINF Operting Systems

# Assignment 7: Basics of Scheduling
## Objective
The goal of this week's assignment is to make you familiar with basic terms and questions concerning scheduling.

## Required Tasks
Answer the following questions

1. **Scheduling -- Process Selection**
When discussing "When to Schedule" in class, it was mentioned that sometimes scheduling could be improved if an important process could play a role in selecting the next process to run when it blocks. Give a situation where this could be used and explain how.

Überlegen Sie eine Situation, in der das Scheduling eines Systems verbessert werden würde, wenn ein wichtiger Prozess, sobald dieser blockiert, eine Rolle bei der Auswahl des nächsten laufenden Prozesses spielen könnte.

2. **Minimizing Turn Around Time**
Imagine the following list of processes in ready state:

Nehmen Sie folgende Liste von Prozessen im Status Ready an:

| Process |A | B | C | D | E | F | G | H |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
Expected run time (msec) | 8 | 5 | 16 | 12 | 55 | 21 | 2 | 34
---

How should a scheduler order these processes to minimize average turn around time? What is the minimal average turn around time in the optimal order you found?

In welcher Reihenfolge muss ein Scheduler diese Prozesse anordnen, damit die durchschnittliche turn around Zeit minimiert wird? Was ist die durchschnittliche turn around Zeit in Ihrer optimalen Anordnung?

3. **Shortest Process Remaining Time Next (SPRTN)**
Consider the following job queue of a SPRTN scheduler:

| Process |G | B | A | D | C | F | H | E |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
Expected run time (msec) | 2 | 5 | 8 | 12 | 16 | 21 | 34 | 55
---

Give a scenario where SPRTN gives a different result compared to Shortest Process Next (SPN). Example: if a new job arriving in the queue would have an estimated runtime of 40 msec it would be added at the last but one position of the queue no matter whether SPRTN or SPN scheduling is used. Give now an example where a newly arriving job would be handled differently in the two different scheduling strategies.

Geben Sie ein Szenario an in welchem SPRTN anders schedulen würde, als Shortest Process Next (SPN). Beispiel: wenn ein neuer Job mit einer geschätzten Laufzeit von 40 msce in die Queue eingereiht wird, würde er in beiden Strategien an die vorletzte Stelle gereiht werden. Geben Sie nun ein Beispiel an, in welchem ein neu zu reihender Job von SPRTN und SPN unterschiedlich behandelt werden würde.
