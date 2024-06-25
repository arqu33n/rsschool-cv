# Alisa Shabanova

**Contact info:**

- **Phone:** +7 (952) 041-57880
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

## Work Experience

### Frontend Developer, Skyeng

_May 2022 - Present_

- Development and maintenance of landing pages (JavaScript, jQuery, jQuery AJAX)
- Integration with APIs (XMLHttpRequest, Fetch API, Google Apps Script API, Firebase API)
- Layout based on Figma designs (HTML, CSS, GSAP animations)
- Technical documentation management
- Integration with external services (CDP - Bloomreach, CRM)
- Project management in Jira, Miro
- SEO tasks (UTM)
- Data analysis in Google Analytics, Yandex Metrica, Yandex DataLens
- CJM analysis, case studies of poor UX
- A/B testing and experiments (using Exponea Bloomreach, GA, Yandex Metrica)
- Working with legacy code, maintenance and refactoring

### Web Designer, Kazmetrostroi

_Sep 2019 - May 2022_

- Design and development of websites on Tilda
- Data analysis in Yandex Webmaster
- Integration with Google Spreadsheets
- UI/UX analysis

### Frontend Web Developer (Internship), Innopolis

_Oct 2021 - Jan 2022_

- Development of a marketplace (ReactJS + Redux)
- Layout based on Figma designs (HTML, SCSS/SASS)
- Using BEM methodology
- Using libraries (Material UI)
- Page navigation (React Router)
- API integration: rendering product catalog, product details, recommendation feed (Fetch API)
- State management: adding products to cart, rendering added products, displaying product name, quantity, and price (Redux)

---

## Education

### Professional Retraining, Frontend Developer

_Innopolis, 2021 - 2022_

### Bachelor of Architecture, BArch, Architectural Engineering

_Kazan State University of Architecture and Engineering, 2014 - 2019_

### Additional Training

- Training "Web Development with React", Hexlet, 2024

---

## Languages

- **English:** B2
- **Russian:** Native
