# Dmitry Valevich

Junior Frontend Developer

---

## Contact information:
* **Phone:** +38 068 4489766
* **E-mail:** ankaholoshina@gmail.com
* **Telegram:** @hannavoloshyna
* **LinkedIn:** [LinkedIn Profile](https://linkedin.com)
* **Behance:** [Behance Portfolio](https://behance.net)

---

## Briefly About Myself:
Having started my career as a layout designer in a local newspaper with minimum skills, I became proficient in printing design. My keen interest in printing technologies led me to working as a Prepress and DTP Engineer in the largest printing house in my city, where I continued self-learning, examining the process of creating wine and food labels, magazines and other printed goods.

Three years ago I've become passionate about retouching. I've mastered different retouching techniques, learned to work with graphic tablet, become an advanced Photoshop user and found my first job as a retoucher.

Remote work as a retoucher gives me extra free time, which I spend learning Frontend Development. I'm interested in Web Development because this occupation provides endless possibilities for professional growth, besides there's a huge amount of free high quality resources for self-education and a large community of developers.

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

---

## Skills and Proficiency:
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code, IntelliJ IDEA
* Adobe Photoshop, Illustrator, InDesign

---

## Code example:
*Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left most index.*

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

---

## Courses:
* JavaScript Manual on [learn.javascript.ru](https://javascript.ru) (in progress)
* RS Schools Course <JavaScript/Front-end. Stage 0> (in progress)

---

## Languages:
* **English:** Intermediate/Upper-intermediate (according to the online test at EF SET [www.efset.org](https://efset.org)) - **PROFICIENT English Level**
