# Alisa Shabanova

**Contact info:**

- **Phone:** +7 (952) 041-78957880
- **Email:** arqu33n@gmail.com
- **LinkedIn:** [linkedin.com/in/arqu33n](https://www.linkedin.com/in/arqu33n/)
- **GitHub:** [github.com/arqu33n](https://github.com/arqu33n)

---

## Summary

Clean, security and UX friendly solutions believer

---

## Skills

### Programming Languages

- **JavaScript**
- **Basic TypeScript**

### Frontend Frameworks and Libraries

- **ReactJS, Next.js**
- **Redux**

### Tools and Utilities

- **ESLint, Prettier**

### UI and Styling

- **UI Libraries**
- **Responsive Design**
- **Figma to HTML/CSS**
- **CSS/SCSS/SaSS**

### Version Control

- **Git, GitLab, GitHub**

### AJAX and Other Technologies

- **jQuery AJAX**

---

## Code Examples

```js
function parse(data) {
  let result = [];
  let counter = 0;
  data.split("").forEach((item) => {
    if (item == "i") {
      counter++;
    } else if (item == "d") {
      counter--;
    } else if (item == "s") {
      counter **= 2;
    } else if (item == "o") {
      result.push(counter);
    } else return;
  });
  return result;
}
```

```js
function createPhoneNumber(numbers) {
  const numbersHost = numbers.toString().replaceAll(",", "");
  const formattedNumber = `(${numbersHost.slice(0, 3)}) ${numbersHost.slice(
    3,
    6
  )}-${numbersHost.slice(6, 10)}`;
  return formattedNumber;
}
```

---
