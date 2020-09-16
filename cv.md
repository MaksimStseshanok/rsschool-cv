# Maksim Stseshanok

### E-mail: maksim.stseshanok@gmail.com

### Linkedin: [Maksim Stseshanok](https://www.linkedin.com/in/maksim-stseshanok/)

#### I am looking for a company that is ready to accept a diligent developer with no work experience. Over the past six months, I have completed two courses in front-end development and really want to realize myself as a specialist in this area.

#### My conception about ideal work:

- interesting and challenging tasks
- opportunities for professional growth
- friendly working atmosphere

### **My skills:**

##### \* Programming languages and skills:

- HTML
- CSS
- JavaScript

##### \* Version control:

- Git
- GitLab

##### \* Methodologies:

- BEM

##### \* Tools:

- Visual Studio Code, Sublime, DevTools, PhotoShop

#### Code examples:

##### Show a modal window corresponding to the name of the pressed button.

```

import { createModalForm } from "./createModalForm.js";
import { createModalAbout } from "./createModalAbout.js";
import { showForm } from "./showForm.js";
import { showAbout } from "./showAbout.js";

export const showModalForm = () => {
  createModalForm();
  createModalAbout();

  document.addEventListener("click", () => {
    let click = event.target.innerText;
    if (click === "Вход") {
      showForm();
    } else if (click === "Об игре") {
      showAbout();
    }
  });
};
```

#### Professional experience:

| Date           | Work                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| September 2020 | Write a mini-game "geometric shapes" using [PixiJS](https://www.pixijs.com/):<br>- On the playing field in arbitrary places there are geometric shapes (up to 10 pieces of only 3 different types - triangle, circle, square), their size, rotation, color and position are chosen randomly. At the bottom of the screen there are 3 shapes (triangle, circle, square) where you need to move the shapes from above, if the shape type matches, then the shape from above disappears, if not, then it returns to its place;<br>- **[Source code](https://github.com/MaksimStseshanok/pixiProject)** |
| July 2020      | Cross-browser SPA:<br>- Game "Football tactics" using localStorage for user registration and authorization;<br>- **[Source code](https://github.com/MaksimStseshanok/footballTactics)**                                                                                                                                                                                                                                                                                                                                                                                                             |
|                |

#### Courses:

##### - [IT-Academy](https://www.gomel.it-academy.by/) - Educational Center for Programming and High Technologies:

Course "Website Development Using HTML, CSS and JavaScript"

##### - [IT-Academy](https://www.gomel.it-academy.by/) - Educational Center for Programming and High Technologies:

Course "JavaScript Web Application Development"

#### Language skills:

- English: A1+
