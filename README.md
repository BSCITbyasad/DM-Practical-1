# Welcome to BSC.IT PRACTICALS

## Hey! I am Asad Shaikh, Student of FY-Bsc.IT. This Webpage is just for the reference and for the revision purpose only.

## Practical No:- 1
### Name of the Practical: **Inclusion Exculsion Principle**

So let's Start With the Question

```markdown
Q.1) In a college 120 mathematics students can opt French, German and Russian.  
Consider the following data:

65 study French
25 study French and German
45 study German
25 study French and Russian
8 study all three languages,  
42 study Russian
15 study German and Russian.
```
### **Lets Solve and Write the Scilab Code**


**Let's Write some Statements**
```markdown
Let T =  Set of 120 mathematics students in college
Let F  =  Set of student studying  French
Let G  =  Set of student studying  German
Let R  =  Set of student studying   Russian
We know that, 
F = 65,  G = 45,  R = 42, F∩G = 20, F∩R = 25, F∩G∩R= 8
```

**Consider some Variables in Scilab Codes**

```markdown
1. T =  120; //Total no. of students.
2. F = 65; // No of students studing French.
3. G = 45; // No of students studing German.
4. R = 42; // No of students studing Russian.
5. FandG = 20; // No of students studing French and german
6. FandR=25; // No of students studing French and Russian.
7. GandR = 15; // No of students studing German and Russian
8. FandGandR= 8; // No of students studing All three langauges.
```

**1.Number of mathematics students taking at least one of the three languages French(F), German(G), or Russian(R).**

Aleast one subject means students can study at leat 1 subject or more than 1 is also valid. So, We have to find (F or G or R) 

Digram:- 

![output 1](https://i.ibb.co/mvr20db/colour-code.png)

**`code will be`**

```markdown
9. ForGorR= F+G+R-FandR-GandR-FandG+FandGandR;
10. disp(ForGorR, 'students taking at least one of the three languages French(F), German(G), or Russian(R)');
```
**Output:-**

![output 1](https://i.ibb.co/F57pqP9/1-answer.png)

**2.Number of students studying French or German or Russian**

'It is Same as the **_Question 1_**. Here also we have to find (F or G or R)'
Output will be same 

**3.Number of students studying French and Russian but not German**

Diagram:-

![Digram](https://i.ibb.co/7WH2wnb/3-question.png)

**`code will be`**

```markdown
11. FRnotG=FandR-FandGandR; // Intersection of French and German - Intersection of  F and R and G.
12. disp(FRnotG, 'Number of students studying French and Russian but not German'); //Result
```

**Output:-**

![output 3](https://i.ibb.co/mXrjgph/3-answer.png)

**4.Number of students studying German and Russian but not French**

Diagram:-

![Digram](https://i.ibb.co/YWGN01x/4-question.jpg)

**`code will be`**
```markdown
13. GRnotF=GandR-FandGandR; // Intersection of German and Russain - Intersection of  F and R and G.
14. disp(GRnotF, 'Number of students studying German and Russian but not French'); //Result
```
**Output:-**

![output 4](https://i.ibb.co/w6M4x1N/4-answer.png)


**5. Number of students studying only French**

Diagram:-

![Digram](https://i.ibb.co/MMwg8PJ/5-question.jpg)

**`code will be`**
```markdown
15. OF= F - FandG-FandR+FandGandR; 
16. disp(OF, 'Number of students studying only French'); //result
```
**Output:-**

![output 5](https://i.ibb.co/84bSkwt/5-answer.png)

**6. Number of students studying only German**

Diagram:-

![Digram](https://i.ibb.co/Jr979h5/6-question.jpg)

**`code will be`**
```markdown
17. OG=G-FandG-GandR + FandGandR;
18. disp(OG, 'Number of students studying only German'); //result
```
**Output:-**

![output 6](https://i.ibb.co/c88HnTF/6-answer.png)


**7. Number of students studying only Russian**

Diagram:-

![Digram](https://i.ibb.co/0nCWc6x/7-question.jpg)

**`code will be`**
```markdown
19. OR= R-FandR-GandR+FandGandR;
20. disp(OR, 'students studying only Russian'); //result
```
**Output:-**

![output 7](https://i.ibb.co/60X0R9W/7-answer.png)


**8. Number of students not studying any of the languages**
In this question we will find **( F or G or R)'**
Diagram:-

![Digram](https://i.ibb.co/ZH53Hnq/8-question.jpg)

**`code will be`**
```markdown
21. NO= T - ForGorR; // Total no. of students - F or G or R. 
22. disp(NO, 'students not studying any of the languages'); //result

```
**Output:-**

![output 8](https://i.ibb.co/HPR3Y5x/8-answer.png)

### Thank you All





