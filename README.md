# Ildar Khasanov

## Contacts

- **Location:** Tomsk, Russia
- **Email:** ildar.hassan@bk.ru
- **GitHub:** [hassan084](https://github.com/hassan084)
- **Skype:** Ildar Hassanov

## About Me

I had graduated master degree of power electrical engineering from Tomsk polytechnic university.
I wanted to find well paid  job according to my major, but it is impossible not to go to deep north of Russia.
I launched some reselling business. One day talked to my ex-groupmate And he told me about good possibilities in IT sphere.
After that I started to learn online courses and do tasks using Java, JavaScript run applications uing docker containers.
Now I want to get a job.

## Skills

- HTML5, CSS3
- Java Core, Spring Framework
- JavaScript Basics
- SQL
- Git
- VS Code, Intellij IDEA

## Code example

**Peak array index KATA from CODEWARS:**
*Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```javascript
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```

## Courses

- [RS SCHOOL. «JavaScript/Front-end»](https://rs.school/js)
- [JAVARUSH](https://javarush.ru/)

## Languages

- **Russian:** native
- **English:** intermediate
