# Lesson plan
  
---

```
/* Start Part 1 */
.flex-container1 {
  display: flex;
}

.flex-container1 div {
  background: peachpuff;
  border: 4px solid brown;
  height: 100px;

  /* Edit below: */
  flex-grow: 1;
  flex-shrink: 1;
  flex-basis: 0;
}

.flex-container1 .two {
  /* Edit below: */
  flex-grow: 2;
  flex-shrink: 1;
  flex-basis: 0;
}
/* End Part 1 */





/* Start Part 2 */
.flex-container2 {
  display: flex;
}

.flex-container2 div {
  background: peachpuff;
  border: 4px solid brown;
  height: 100px;
  
  /* Edit below: */
  flex-grow: 1;
  flex-shrink: 1;
  flex-basis: auto;
}

.flex-container2 .two {
  /* Edit below: */
  width: 200px;
  flex-grow: 1;
  flex-shrink: 0;
  flex-basis: auto;
}
/* End Part 2 */






/* Start Part 3 */
.flex-container3 {
  display: flex;
}

.flex-container3 div {
  background: peachpuff;
  border: 4px solid brown;
  height: 100px;

  /* Edit below: */
  flex-grow: 1;
  flex-shrink: 1;
  flex-basis: 0;
}

.flex-container3 .two {
  /* Edit below: */
  flex-grow: 1;
  flex-shrink: 1;
  flex-basis: 250px;
}
/* End Part 3 */

```