# Emmet-Cheat-Sheet
---

# **Emmet Cheat Sheet for Fast HTML Coding**

## **Table of Contents**
1. [Basic Elements](#basic-elements)
2. [Nesting Elements](#nesting-elements)
3. [Attributes](#attributes)
4. [Classes and IDs](#classes-and-ids)
5. [Multiplication](#multiplication)
6. [Sibling Elements](#sibling-elements)
7. [Grouping](#grouping)
8. [Text and Content](#text-and-content)
9. [Numbering](#numbering)
10. [Custom Snippets](#custom-snippets)

---

## 1. **Basic Elements**
Quickly create common HTML tags.

- `div` → `<div></div>`
- `a` → `<a href=""></a>`
- `p` → `<p></p>`
- `img` → `<img src="" alt="">`

---

## 2. **Nesting Elements**
Easily nest elements using `>`.

- `ul>li` → 
  ```html
  <ul>
      <li></li>
  </ul>
  ```
- `div>h1+p` →
  ```html
  <div>
      <h1></h1>
      <p></p>
  </div>
  ```

---

## 3. **Attributes**
Set attributes directly with brackets `[]`.

- `a[href="https://example.com"]` → 
  ```html
  <a href="https://example.com"></a>
  ```
- `img[src="/path/to/image.jpg"][alt="Image description"]` →
  ```html
  <img src="/path/to/image.jpg" alt="Image description">
  ```

---

## 4. **Classes and IDs**
Use `.` for classes and `#` for IDs.

- `div.container` → `<div class="container"></div>`
- `div#header` → `<div id="header"></div>`
- `button.btn.primary` → `<button class="btn primary"></button>`

---

## 5. **Multiplication**
Create multiple elements using `*`.

- `ul>li*3` →
  ```html
  <ul>
      <li></li>
      <li></li>
      <li></li>
  </ul>
  ```
- `p*2` →
  ```html
  <p></p>
  <p></p>
  ```

---

## 6. **Sibling Elements**
Use `+` to create sibling elements.

- `h1+p` →
  ```html
  <h1></h1>
  <p></p>
  ```
- `header+main+footer` →
  ```html
  <header></header>
  <main></main>
  <footer></footer>
  ```

---

## 7. **Grouping**
Group elements with parentheses `()`.

- `(div>h1)+footer` →
  ```html
  <div>
      <h1></h1>
  </div>
  <footer></footer>
  ```

---

## 8. **Text and Content**
Use curly braces `{}` to add content.

- `p{Hello, World!}` → `<p>Hello, World!</p>`
- `a[href="https://example.com"]{Visit Here}` →
  ```html
  <a href="https://example.com">Visit Here</a>
  ```

---

## 9. **Numbering**
Use `$` to create numbered elements.

- `ul>li.item$*3` →
  ```html
  <ul>
      <li class="item1"></li>
      <li class="item2"></li>
      <li class="item3"></li>
  </ul>
  ```

---

## 10. **Custom Snippets**
Define reusable abbreviations for complex structures.

- `nav>ul>li*3>a[href="#"]{Link $}` → 
  ```html
  <nav>
      <ul>
          <li><a href="#">Link 1</a></li>
          <li><a href="#">Link 2</a></li>
          <li><a href="#">Link 3</a></li>
      </ul>
  </nav>
  ```

---

### **Bonus Tips**
- **Expansion:** Type your Emmet abbreviation and hit `Tab` to expand.
- **Customization:** You can define custom Emmet snippets in your editor for more efficiency.

---

This cheat sheet will help users quickly build HTML structures using Emmet shortcuts!
