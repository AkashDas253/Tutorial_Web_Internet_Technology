## **Web Technologies (9 Hours)**

---

### **1. HTML (3L)**

#### **Introduction**

* **HTML (HyperText Markup Language)** is the standard language for creating web pages.
* Structure: Elements enclosed in angle brackets (`< >`), forming a hierarchical document.

#### **HTML Editors**

* Text-based: Notepad, Sublime Text, VS Code.
* WYSIWYG: Adobe Dreamweaver, online builders.

#### **Core HTML Elements**

| Element  | Purpose                                           |
| -------- | ------------------------------------------------- |
| `<html>` | Root element of an HTML page                      |
| `<head>` | Contains metadata, title, links to scripts/styles |
| `<body>` | Main visible content of the page                  |

#### **Common Elements**

* **Headings**: `<h1>` to `<h6>`
* **Paragraphs**: `<p>`
* **Line Break**: `<br>`, **Horizontal Rule**: `<hr>`
* **Text Formatting**: `<b>`, `<i>`, `<u>`, `<em>`, `<strong>`, `<mark>`, `<sup>`, `<sub>`

#### **Attributes**

* Key-value pairs inside tags: `name="value"`
* Examples: `id`, `class`, `href`, `src`, `style`, `alt`, `title`

#### **Links**

* `<a href="url">text</a>`
* Target attribute: `_blank`, `_self`, `_parent`, `_top`

#### **Lists**

* Ordered List: `<ol>`, Unordered List: `<ul>`, Definition List: `<dl>`

#### **Tables**

* Elements: `<table>`, `<tr>`, `<td>`, `<th>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`

#### **Block vs Inline**

| Type   | Examples                             |
| ------ | ------------------------------------ |
| Block  | `<div>`, `<p>`, `<table>`, `<form>`  |
| Inline | `<span>`, `<a>`, `<img>`, `<strong>` |

#### **HTML Layout**

* `<div>`, `<section>`, `<article>`, `<header>`, `<footer>`, `<nav>`, `<aside>`

#### **CSS Introduction**

* Inline, Internal, External CSS
* Syntax: `selector { property: value; }`
* Selectors: element, class (`.class`), id (`#id`)
* Positioning: static, relative, absolute, fixed
* Box Model: content, padding, border, margin

#### **Forms**

* `<form>` with input elements like `<input>`, `<textarea>`, `<select>`, `<button>`
* Attributes: `action`, `method`, `name`, `value`, `placeholder`, `required`, `autocomplete`

#### **Iframe**

* `<iframe src="url"></iframe>`: Embeds another document
* Attributes: `width`, `height`, `title`, `frameborder`

#### **Colors**

* **Color Names**: `red`, `blue`, `green`, etc.
* **Color Values**: Hex (`#FF0000`), RGB (`rgb(255,0,0)`), RGBA, HSL

---

### **2. Image Maps (1L)**

#### **Image Map Elements**

* `<map name="mapname">`: Container for clickable areas.
* `<area>`: Defines each clickable area.

#### **Attributes of `<area>`**

| Attribute | Description                                 |
| --------- | ------------------------------------------- |
| `shape`   | `rect`, `circle`, `poly`                    |
| `coords`  | Coordinates of the area (varies with shape) |
| `href`    | Target URL                                  |
| `alt`     | Alternative text                            |
| `target`  | Link target window                          |

---

### **3. XML (4L)**

#### **Introduction**

* **XML (eXtensible Markup Language)** is a markup language for data representation and exchange.
* Not for presentation like HTML.

#### **Tree Structure**

* Hierarchical document structure.
* Root → Parent → Child elements.

#### **Syntax Rules**

* Must have one root element.
* Tags are case-sensitive.
* Elements must be properly nested and closed.

#### **Elements and Attributes**

| Feature    | Description                                              |
| ---------- | -------------------------------------------------------- |
| Elements   | Represent data content using `<tag>value</tag>`          |
| Attributes | Provide metadata inside opening tag `<tag attr="value">` |

#### **Validation**

* **DTD (Document Type Definition)** and **XSD (XML Schema Definition)** ensure structural correctness.

#### **Viewing XML**

* Can be viewed in web browsers.
* Parsers used in applications: DOM, SAX.

#### **XHTML in Brief**

* **XHTML (eXtensible HTML)**: Stricter HTML based on XML syntax.
* Follows well-formed rules: lowercase tags, closed elements, quoted attributes.

---

### **4. CGI Scripts (1L)**

#### **Introduction**

* **CGI (Common Gateway Interface)** enables web server to execute external programs (scripts) and send output to client.

#### **Environment Variables**

* Server passes request data through environment variables:

  * `QUERY_STRING`, `REQUEST_METHOD`, `CONTENT_LENGTH`, `REMOTE_ADDR`, etc.

#### **GET and POST Methods**

| Method | Description                                                   |
| ------ | ------------------------------------------------------------- |
| GET    | Sends data via URL query string; visible and limited in size  |
| POST   | Sends data in request body; used for large and sensitive data |

---

## Summary Table

| Section     | Key Topics                                                                            |
| ----------- | ------------------------------------------------------------------------------------- |
| HTML        | Syntax, Editors, Tags, Attributes, Layout, Tables, Lists, Forms, CSS, Colors, Iframes |
| Image Maps  | `<map>`, `<area>`, shapes and attributes                                              |
| XML         | Tree structure, Elements, Attributes, Syntax, Validation (DTD/XSD), Viewing, XHTML    |
| CGI Scripts | Script execution, Environment variables, GET/POST methods                             |

---
