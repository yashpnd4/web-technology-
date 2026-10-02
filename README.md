# 🌐 Web Technologies (WT) Practicals

A comprehensive collection of practical lab experiments, reference notes, and working examples covering fundamental concepts of the **World Wide Web (WWW)**, **HTTP/Network Protocols**, **HyperText Markup Language (HTML)**, **HTML5 Semantic Elements**, and **XML Fundamentals**.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Repository Structure](#-repository-structure)
- [Modules & Topics Breakdown](#-modules--topics-breakdown)
  - [Module 01: World Wide Web (WWW) & Networking](#module-01-world-wide-web-www--networking)
  - [Technical Comparisons](#technical-comparisons)
  - [Module 02: HyperText Markup Language (HTML) & HTML5](#module-02-hypertext-markup-language-html--html5)
- [How to Run and View the Practicals](#-how-to-run-and-view-the-practicals)
- [Key Learning Outcomes](#-key-learning-outcomes)
- [Roadmap & Upcoming Modules](#-roadmap--upcoming-modules)
- [License & Acknowledgements](#-license--acknowledgements)

---

## 📖 Overview

This repository contains structured, standalone HTML practicals designed for academic computer science and web development laboratory curriculums. The practicals serve both as self-contained study notes and live browser-renderable demonstration files.

Each topic is organized logically with clear theoretical explanations, syntax guides, illustrative diagrams, comparison tables, and code snippets demonstrating core web standards.

---

## 📂 Repository Structure

```text
html1/
└── WT PRACTICALS/
    └── main/
        ├── main.html                 # Central portal / entry dashboard
        ├── html/                     # Module 02: HTML & HTML5 Practicals
        │   ├── html.html             # HTML Module Index & Navigation Hub
        │   ├── basics-of-html.html   # Basic structure, elements, tags & attributes
        │   ├── formatting-and-fonts.html # Text formatting, fonts, display rules
        │   ├── colors-and-hyperlinks.html # Color models, absolute & relative links
        │   ├── lists-tables-images-forms.html # Lists, tables, media & form controls
        │   └── html5-and-xml.html    # HTML5 semantic elements, multimedia & XML
        └── www/                      # Module 01: WWW & Networking Foundations
            ├── www.html              # WWW Module Index & Navigation Hub
            ├── 1st.html              # History & Evolution of WWW (Web 1.0 to 4.0)
            ├── 2nd.html              # HTTP Protocol, architecture, methods & status codes
            ├── 3rd.html              # Uniform Resource Locators (URL structure & parts)
            ├── 4th.html              # DNS architecture, hierarchy & name resolution
            ├── 5th.html              # IP addressing, security & privacy protection
            ├── 6th.html              # Web designing principles & client vs. server architecture
            ├── d1.html               # Comparison: Internet vs. World Wide Web
            ├── d2.html               # Comparison: URL vs. URI
            ├── d3.html               # Comparison: Web Browser vs. Web Server
            ├── d4.html               # Comparison: IPv4 vs. IPv6
            └── d5.html               # Comparison: IP Address vs. MAC Address
```

---

## 📚 Modules & Topics Breakdown

### Module 01: World Wide Web (WWW) & Networking

Accessible via: `WT PRACTICALS/main/www/www.html`

| File | Topic Title | Key Concepts Covered |
| :--- | :--- | :--- |
| [`1st.html`](WT%20PRACTICALS/main/www/1st.html) | **History & Concept of WWW** | Invention at CERN (Tim Berners-Lee), First browser/server, Web 1.0 (static), Web 2.0 (social/interactive), Web 3.0 (semantic), Web 4.0 (AI/decentralized). |
| [`2nd.html`](WT%20PRACTICALS/main/www/2nd.html) | **HTTP Protocol** | Hypertext Transfer Protocol mechanism, Client-Server handshake, Request/Response headers, HTTP Methods (`GET`, `POST`, `PUT`, `DELETE`), Status codes (`2xx`, `3xx`, `4xx`, `5xx`). |
| [`3rd.html`](WT%20PRACTICALS/main/www/3rd.html) | **All About URLs** | URL anatomy: Protocol/Scheme, Domain/Host, Port, Path, Query string parameters, Fragment/Anchor identifier. |
| [`4th.html`](WT%20PRACTICALS/main/www/4th.html) | **DNS & Its Purpose** | Domain Name System hierarchy (Root, TLD, Authoritative DNS), DNS resolution workflow, Record types (`A`, `AAAA`, `CNAME`, `MX`). |
| [`5th.html`](WT%20PRACTICALS/main/www/5th.html) | **IP Address & Protection** | IPv4 & IPv6 specifications, Static vs. Dynamic IPs, Public vs. Private address space, Security measures (Firewalls, VPNs, NAT). |
| [`6th.html`](WT%20PRACTICALS/main/www/6th.html) | **Web Designing Concepts** | UI vs. UX fundamentals, Responsive web design (RWD), Layout principles, Client-side vs. Server-side processing, accessibility basics. |

---

### ⚖️ Technical Comparisons

Detailed tabular comparisons of frequently tested web engineering concepts:

| File | Comparison | Key Distinctions Highlighted |
| :--- | :--- | :--- |
| [`d1.html`](WT%20PRACTICALS/main/www/d1.html) | **Internet vs. WWW** | Physical global network infrastructure vs. application-layer information-sharing system built atop it. |
| [`d2.html`](WT%20PRACTICALS/main/www/d2.html) | **URL vs. URI** | Identifier (URI) vs. Specific Locator specifying protocol and resource path (URL). |
| [`d3.html`](WT%20PRACTICALS/main/www/d3.html) | **Web Browser vs. Web Server** | Client-side rendering application (Chrome, Firefox) vs. Host daemon serving requests (Apache, Nginx). |
| [`d4.html`](WT%20PRACTICALS/main/www/d4.html) | **IPv4 vs. IPv6** | 32-bit address space, dotted decimal notation vs. 128-bit address space, hexadecimal format and auto-configuration. |
| [`d5.html`](WT%20PRACTICALS/main/www/d5.html) | **IP Address vs. MAC Address** | Logical Layer 3 routable address vs. Physical Layer 2 hardware address burned into the NIC. |

---

### Module 02: HyperText Markup Language (HTML) & HTML5

Accessible via: `WT PRACTICALS/main/html/html.html`

| File | Topic Title | Key Concepts Covered |
| :--- | :--- | :--- |
| [`basics-of-html.html`](WT%20PRACTICALS/main/html/basics-of-html.html) | **Basics of HTML** | Anatomy of tags, opening/closing tags, void elements, core document layout (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`), heading hierarchy (`<h1>`-`<h6>`), paragraphs, line breaks (`<br>`), horizontal rules (`<hr>`). |
| [`formatting-and-fonts.html`](WT%20PRACTICALS/main/html/formatting-and-fonts.html) | **Formatting and Fonts** | Text formatting (`<b>`, `<strong>`, `<i>`, `<em>`, `<u>`, `<mark>`, `<small>`, `<sub>`, `<sup>`), preformatted text (`<pre>`), quotations (`<blockquote>`, `<q>`), font styling attributes. |
| [`colors-and-hyperlinks.html`](WT%20PRACTICALS/main/html/colors-and-hyperlinks.html) | **Colors and Hyperlinks** | Color systems (Hex `#RRGGBB`, RGB values, named colors), Anchor tag (`<a>`), relative vs. absolute URLs, opening links in new tabs (`target="_blank"`), internal page bookmark anchors, mailto links. |
| [`lists-tables-images-forms.html`](WT%20PRACTICALS/main/html/lists-tables-images-forms.html) | **Lists, Tables, Images & Forms** | • **Lists**: Ordered (`<ol>`), Unordered (`<ul>`), Nested & Description lists (`<dl>`, `<dt>`, `<dd>`).<br>• **Tables**: `<table>`, `<tr>`, `<th>`, `<td>`, `border`, `cellpadding`, `cellspacing`, `colspan`, `rowspan`.<br>• **Images**: `<img>` element, `src`, `alt`, dimensions.<br>• **Forms**: `<form>`, text inputs, password fields, radio buttons, checkboxes, `<select>` dropdowns, textareas, submit & reset actions. |
| [`html5-and-xml.html`](WT%20PRACTICALS/main/html/html5-and-xml.html) | **HTML5 & XML** | • **XML Fundamentals**: Syntax rules, well-formed tree, root element, attribute quoting, XML declarations.<br>• **HTML5 Semantics**: `<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`.<br>• **Multimedia**: Native `<audio>` and `<video>` elements.<br>• **HTML5 Form Inputs**: `email`, `number`, `range`, `date`, `color`, `url`. |

---

## 🚀 How to Run and View the Practicals

Because all practicals are built using standard Vanilla HTML, no server installation or build step is required:

### Option 1: Direct Browser Launch
1. Navigate into `WT PRACTICALS/main/` in your file explorer.
2. Double-click **`main.html`** to open the main navigation portal in your default browser (Google Chrome, Firefox, Edge, etc.).
3. Use the interactive menu links to navigate to any module or practical topic.

### Option 2: Using VS Code Live Server Extension
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey) if not already installed.
3. Right-click on `main.html` and select **"Open with Live Server"**.
4. The practicals will launch at `http://127.0.0.1:5500/WT%20PRACTICALS/main/main.html` with hot-reloading enabled.

---

## 🎯 Key Learning Outcomes

Upon going through these practicals, students and learners will understand:
- The distinction between network infrastructure (Internet) and application protocols (Web, HTTP, DNS).
- Complete packet addressing schemes (IP vs. MAC, IPv4 vs. IPv6).
- How to structure modern, accessible web pages using semantic HTML5 markup.
- How to build multi-page websites connected through relative and absolute hyperlinks.
- Designing complex data presentations with nested lists and merged table cells (`rowspan`/`colspan`).
- Capturing user input using accessible, valid HTML forms with varied control types.
- The fundamental syntax rules governing data storage and transmission via XML.

---

## 🗺️ Roadmap & Upcoming Modules

The central dashboard (`main.html`) includes placeholders for future laboratory units:
- [ ] **Module 03**: Introduction to CSS (Cascading Style Sheets, selectors, box model, Flexbox, Grid)
- [ ] **Module 04**: Introduction to JavaScript (Variables, functions, DOM manipulation, event handling)
- [ ] **Module 05**: Introduction to XML & DTD/XSD (Schemas, parsing, and XSLT transformations)
- [ ] **Module 06**: Introduction to PHP & Server-Side Scripting (Form handling, session management, database connectivity)

---

## 💻 Tech Stack & Tools

- **Markup & Styling**: Pure HTML4 / HTML5 (Zero heavy external dependencies)
- **Compatibility**: All modern standards-compliant web browsers (Chrome, Edge, Firefox, Safari, Opera)
- **Design Philosophy**: Academic reference clarity with accessible tabular presentation and color-coded sections.
