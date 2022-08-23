## 5 Easy ways to align content vertically center

[![youtube](https://img.shields.io/badge/WebsCode%20Media-Youtube-red?style=for-the-badge&logo=appveyor "Youtube")](https://www.youtube.com/channel/UCzk-Ck1hnzEl44Y7PASfA7Q)

![HTML](./html5.svg "HTML 5") ![CSS](./css3.svg "CSS")

### Please Checkout [Youtube Video.](https://www.youtube.com/watch?v=ICuRrjAG0ZM "youtube video")

### Please Checkout [Codepen.](https://codepen.io/WebsCodeMedia/pen/VwLgYZz "Codepen")

---

### 01. Center Vertically - Using Position & Transform

---

#### HTML

```html
<div class="absolute">
  <p>Vertically Center</p>
</div>
```

#### CSS

```css
.absolute {
  position: relative;
  width: 100%;
  height: 100vh;
}
.absolute p {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

---

### 02. Center Vertically - Using Flexbox

---

#### HTML

```html
<div class="flex">
  <p>Vertically Center</p>
</div>
```

#### CSS

```css
.flex {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
```

---

### 03. Center Vertically - Using Grid

---

#### HTML

```html
<div class="grid">
  <p>Vertically Center</p>
</div>
```

#### CSS

```css
.grid {
  height: 100vh;
  display: grid;
  place-items: center;
}
```

---

### 04. Center Vertically - Using Grid and Margin

---

#### HTML

```html
<div class="grid-margin">
  <p>Vertically Center</p>
</div>
```

#### CSS

```css
.grid-margin {
  height: 100vh;
  display: grid;
}
.grid-margin p {
  margin: auto;
}
```

---

### 05. Center Vertically - Using Tabel

---

#### HTML

```html
<div class="tabel">
  <p>Vertically Center</p>
</div>
```

#### CSS

```css
.tabel {
  width: 100%;
  height: 100vh;
  display: table;
}
.tabel p {
  display: table-cell;
  vertical-align: middle;
  text-align: center;
}
```
