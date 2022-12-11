# Udacity | Landing Page Project

![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/mohamedelgendyx/Udacity-Landing-Page-Project?include_prereleases)

### In This Project We Are Converting A Static Landing Page Into A Dynamic One With The Help Of Javascript.

---

## Table of Contents

-   [Project Title](#Udacity-|-Landing-Page-Project)

-   [Table of contents](#table-of-contents)

-   [Page Preview](#page-preview)

-   [Installation & Usage](#installation-and-usage)

-   [Development](#development)

-   [Contribute](#contribute)

-   [License & Copyright](#License-&-Copyright)

---

## Page Preview

![Page Preview](preview.JPG)

---

## Installation and Usage

[(Back to top)](#table-of-contents)

You can install this project to your PC by downloading It as a ZIP file.

or Clone it using `git clone <repo-url>` .

After the Installation you can now use the project files by unzip the file then open it on any code editor e.g.(VS Code).

---

## Development

[(Back to top)](#table-of-contents)

>
>**_JS Version: ES2015/ES6._**
>
>**_JS Standard: ESlint_**
>

### **The Project Contains Four Files :**


#### *css /*

-   *styles.css*


#### *index.html*

#### *js /*

-   *app.js*

#### *README.md*

#### **Each file contains it's modifications and comment above each step of modify.**

-   In CSS Style there is a lot of change done on the project to be the style you see on screen interface right now, also a lot of modifications to be responsive on all screen types.

-   There's not a lot of modification done in the HTML File it was just adding 2 more sections (4 and 5) to the Page.

-   The majority of the work was done on app.js, there is a lot of things done there:

          1. Use goToSection() method to scroll to anchor ID using scrollIntoView event.

          2. Build NavBar Using navBuilder() function that executed by foreach loop and other helping methods like createMenuLink() to create elements and insert text to it and also appending.

          3. Bulid scroll to up button using createUpButton() function to be easy for the user to click on it to go to the home page again without scrolling.

          4. use isInViewport() method to identify which section is on the viewport to help the isActive() method to give a special class to the sectoin and button in the NavBar to be clearly viewed to the user that this is the actual section he selected.

          5. Toggle the Navbar Visibility according to user interaction with a webpage by checking if he is scrolling or not using the setTimeOut Method.
---

# Contribute

[(Back to top)](#table-of-contents)

**- EgFWD**

**- ITIDA**

**- Udacity**

---

# License & Copyright

[(Back to top)](#table-of-contents)

_© Udacity - Modified By Mohamed Elgendy._
