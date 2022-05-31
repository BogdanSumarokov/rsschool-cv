# Bogdan Sumarokov
![alttext](/assets/image/MyPhoto.jpg)

---

## Contacts: 
* Telegram: @bogdan_sumarokov
* Phone: +7-909-389-47-33
* GitHub: BogdanSumarokov

---

## About me:
> I'm 20 years old. I am a novice frontend developer.  I don't have any work experience yet, but I plan to get it very soon. I now devote almost all my free time to learning programming, and I also like to read and train.

---

## Skills:
1. git - beginner
2. HTML - intermediate
3. CSS - intermediate
4. JS - beginer

---

## Code example:
> Create a function finalGrade, which calculates the final grade of a student depending on two parameters: a grade for the exam and a number of completed projects.
This function should take two arguments: exam - grade for exam (from 0 to 100); projects - number of completed projects (from 0 and above);
This function should return a number (final grade). There are four types of final grades:
100, if a grade for the exam is more than 90 or if a number of completed projects more than 10.
90, if a grade for the exam is more than 75 and if a number of completed projects is minimum 5.
75, if a grade for the exam is more than 50 and if a number of completed projects is minimum 2.
0, in other cases


```
function finalGrade (exam, projects) {
 if((exam > 90) || (projects > 10)){
   return 100;
 } else if ((exam > 75) && (projects >= 5)){
   return 90;
 } else if((exam > 50) && (projects >= 2)){
   return 75;
 } else{
   return 0;
 }
}
```
---
