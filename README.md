Hypatiamat - I Want To Solve Questions About...
====================================

Master's Dissertation - Software Engineering, October 2022

_Defended On_: TBD

_Author_: [Válter Carvalho][valtercarvalho]

## Description

Goes over the development process for two full-stack web applications, built from scratch using [Vue.js](https://vuejs.org/) + [Vuetify](https://vuetifyjs.com/en/), [Strapi](https://strapi.io/) and [MySQL](https://www.mysql.com/).

### I Want to Solve Questions About

Application that allows students from grades 1 through 9 (Portuguese Basic Education) to solve questions related to Maths.

They can be of the following types:
* Multiple Choice - the student has to pick the correct answer from a possible selection of 3 up to 6 different answers;
* True or False - the student has to indicate whether the question statement is true or false;
* Symmetry - the student has to complete a symmetry on the X or Y axis using a grid;
* Open-Ended - the student has a digital keyboard which they use to type in the answer to the question.

This application is a rework of its original version, which got visually and technologically outdated, focusing more on visual appeal, responsiveness, user experience and better usability.

It also features leaderboards, a rotation of questions updated monthly and a favourites page.

### Question Submission Back-Ofice
The owners of Hypatiamat had to manually update the database if they wanted to execute CRUD operations on the questions (currently there are over 3000 of them), which was growing more and more unsustainable due to the increase in complexity.

The back-office's main goal is to allow the owners to execute these CRUD operations via an intermediate form, simplifying the process and lowering the chance of breaking changes due to user error.

This form has to take into account all the different types of questions whilst also maintaining an intuitive and simple interface.

It features a two-step validation process, where any form submission gets quarantined and has to be approved by a different person than the one that submitted it, to ensure that the question only gets added to the final database if it meets all the necessary criteria.

It also has a table where the teachers can choose to hide the question from the students, an ordering system for the theme selector, image linking, search tables with filters and many more other administrative functionalities.

This one is blocked from public access by an authentication lyaer, as it contains sensitive data from the platform and its intended use is only for the owners.

## BibTeX Entry

When citing this paper, please use the following BibTeX entry:
```
@mastersthesis{valtercarvalho2022hypatiamat,
    author = {Válter Carvalho},
    title = {Hypatiamat - I Want To Solve Questions About...},
    school = {University of Minho},
    year = {2022},
    month = {10}
}
```

[](https://raw.githubusercontent.com/glouppe/phd-thesis/master/README.md)

## Links

<!-- links -->
The application is available for public use, you can try it if you want:

* [I Want to Solve Questions About...](https://qr.hypatiamat.com)

_Note_: only available in Portuguese.

[valtercarvalho]: https://github.com/wurzy
[uminho]: localhost
