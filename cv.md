### Olga Belikova

__phone:__ __*+375(44)5592800*__ __email:__ __*lakshmy712@mail.ru*__

I *love to study* something new all the time. I am very *sensitive, emotional* and *creative*. My *highest values* are **harmony, kindness, beauty** and **peace**, and my *dream* is **to make this world a peaceful, harmonious and beautiful place**.

**My skills:**
* _English_ - Upper-Intermediate - Advanced
* _HTML_ - Intermediate
* _CSS_ - Intermediate
* _SCSS_ - Basic - Intermediate
* _Photoshop_ - Basic - Intermediate
* _Git_ - Basic
* _JavaScript_ - Basic
* _React_ - Basic
* _Webpack_ - Basic
* _BEM_ - Basic

**My code examples:**

*A Good function constructor for model*

```
const Good = (function () {
  let counter = 0;
  return function Good(category, price, imgPath, amount, name) {
    this.id = ++counter;
    this.category = '' + category;
    this.price = parseInt(price);
    this.imgPath = '' + imgPath;
    this.amount = parseInt(amount);
    this.name = '' + name;
    this.description = '';
    Object.defineProperty(this, 'id', { writable: false });
    Object.preventExtensions(this);
  };
}());

Object.defineProperty(Good, 'id', { writable: false, enumerable: true });
Object.preventExtensions(Good);


Good.prototype.setDescription = function (description) {
  this.description = description;
  return this;
};

Good.prototype.addUnit = function (value) {
  this.amount += value || 1;
  return this;
};

Good.prototype.reduceUnit = function (value) {
  if (this.amount > 0) {
    this.amount -= value || 1;
    return this;
  }
};
```

*A presentational Card component*

```
import React from 'react';
import './Card.scss';

const Card = ({card}) => (
  <figure className="product">
    <img className="product__image" src={card.imageUrl} alt="Image should be here" />
    <div className="product__price">{card.price}</div>
    <figcaption className="product__description description">
      <p className="description__headline">{card.title}</p>
    </figcaption>
  </figure>
  );

export default Card;
```

All my __experience__ includes just some __projects from the courses__ I attended:
1. [HTML - CSS](https://github.com/olgazed/CSS)
1. [SASS](https://github.com/olgazed/SASS)
1. [Canvas and animation](https://github.com/olgazed/Canvas-Animation)
1. [React](https://gitlab.com/olgazed/volha_belikava/tree/React_Task_2/React_Task2)
1. [HTML - CSS](https://gitlab.com/olgazed/volha_belikava/tree/HTML_CSS_Task1/HTML_CSS_Task1)
1. [HTML - CSS - JS](https://gitlab.com/olgazed/volha_belikava/tree/HTML_CSS_Task2_JS_Task3/Hometasks/HTML_CSS_Task2_JS_Task3)

_(The repository on GitLab is Private, access can be granted upon request.)_

**Education:**
* HTML Academy
* Codecademy
* GeekBrains
* Hexlet
* SoloLearn
* EPAM

**English**
* Minsk State Linguistic University, 1999 - 2004
  * English language and literature
* Life and work in London, 2005 - 2006
* Moscow High School of Social and Economic Sciences, 2006 - 2007
  * English for IELTS, practical psychology