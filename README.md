<a name="top"></a>

# 5. Домашнее задание к лекции «Композиция компонентов»

[![Build status](https://ci.appveyor.com/api/projects/status/emnds7ppt8jc4a6h?svg=true)](https://ci.appveyor.com/project/igor-chazov/ra-hw-5-composition-1-2-3) [[GithubPages](https://igor-chazov.github.io/ra-hw-5_composition_1-2-3)]

---

**Перейти к:**  
***[5.2 Декомпозиция](#5.2)  
[5.3 Collapse*](#5.3)***

---

## 5.1 Карточки

Вам необходимо реализовать компонент карточек, позволяющий использовать себя следующим образом:

![](./assets/card1.png)

![](./assets/card2.png)

В качестве CSS вы можете использовать Bootstrap, а подглядеть генерируемую разметку можете на странице: https://getbootstrap.com/docs/4.3/components/card/

Подсказка: используйте для этого `props.children` и `props` для отображения картинки.

---

## <a name="5.2">5.2 Декомпозиция</a>
***[(наверх)](#top)***

Вы работаете в стартапе, который решил тягаться с самим Яндексом в части предоставления контента. Это, конечно же шутка, но задача нешуточная.

Вам принесли дизайн-макет, похожий на этот:

![](./assets/decomposition.png)

Что вам нужно сделать:

1. Разбейте весь интерфейс на компоненты и в файле каждого компонента напишите буквально одну строку комментария, за что данный компонент отвечает (можете использовать формат JSDoc, подсмотреть можно, например, у ребят из Alfa Laboratory: https://github.com/alfa-laboratory/arui-feather/blob/v16.0.0/src/dropdown/dropdown.jsx).
1. Постарайтесь повторящиеся компоненты сделать настраемыми за счёт `props`. Допустим, у каждой новости в списке новостей: иконка, текст и ссылка.

Функциональность и стилизацию реализовывать не нужно, достаточно базового оформления (чтобы видно было все блоки).

---

## <a name="5.3">5.3 Collapse*</a>
***[(наверх)](#top)***

Вам поручено реализовать аналог компонента Collapse (https://digital.alfabank.ru/components/collapse).

Обратите ключевое внимание на следующие `props`:
* `collapsedLabel`
* `expandedLabel`

Если значения этих `props` не переданы, то они принимают значения по умолчанию `Развернуть` (для `collapsedLabel`) и `Свернуть` (для `expandedLabel`).

Попробуйте также реализовать анимацию с помощью CSS.

---
