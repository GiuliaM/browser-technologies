## Contact list

[Demo](https://giuliam.github.io/browser-technologies/week3/contactlist/index.html)

This demo is a contact list, in which you can search by letter. It's build with the idea of progressive enhancement. Starting with HTML and enhancing it with CSS and Javascript.

- [HTML](#html)

---
## [HTML](#html)
For HTML I used the `<details>` element. This element is used as widget which the user can use to retrieve information.

By using `summary` you can tell the user what information you can find by opening the widget.

<img src="img/html-contact.PNG" alt="Contact list using the detail attribute" height="400px">

Unfortunately not every browser supports the `<details>` attribute.
<img src="img/ciu-details.png" alt="Overview browser support">

This list seems to be a little outdated, because it also works on opera mini. But it doesn't work on Internet Explorer. If `<details>` doesn't work it will show the widget opened. Showing all the information. With CSS you can make hierarchy in the structure.

<img src="img/opera.PNG" alt="Detail element working on Opera Mini" height="400px">
<img src="img/ie-contact.JPG" alt="Detail element showing all the information in the widget" height="300px">


## Source
- [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)
- [Can I use?](http://caniuse.com/#search=detail)
