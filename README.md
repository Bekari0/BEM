# BEM
## 1 задание
<!--блоки-->
голова 
тело
руки

<!--элементы-->
голова__глаза
голова__нос
тело__колено
тело__волосы
руки__пальцы
руки__ногти


<!--модификаторы-->
голова__глаза--форма-узкие
тело__волосы--цвет-карие
руки__пальцы--размер-большие

## 2-4 задание
### header
``` 
header.header>div.header__wrapper>a.header__logo.logo>img.logo__img^nav.header__nav.nav>ul.nav__list>li.nav__item*6>a.nav__link
``` 
![Header](/img/header.png "Header")

### form

```
section.find-out>div.find-out__wrapper>h2.find-out__heading+form.find-out__form.form>label.form__label*2>select.form__select>option.form__option*3^^label.form__label*3>input.form__input^button.form__button
```
![form](/img/form.png)

### card 

```
section.card>div.card__wrapper>h2.card__heading+ul.card__list>li.card__item.item*3>img.item__img+p.item__heading+p.item__description
```
![card](/img/card.png)

### other
```
section.benefits>div.benefits__wrapper>h2.benefits__heading+ol.benefits__list>li.benefits__efficiency-card*8>img.benefits__img+p.benefits__description
```
![other](/img/other.png)