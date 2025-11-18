# Frontend Development Roadmap

## 📘 HTML Roadmap (6 Hours — 2 Sessions × 3 Hours)

This roadmap covers everything you need to master HTML fundamentals and build clean, semantic, and accessible web pages.  
HTML is the foundation of all frontend work, so these 2 intensive sessions cover all essential tags, structure, and practices.

---

## 🕒 Session 1 — HTML Foundations, Structure & Core Elements (3 Hours)

**What you will learn:**

### 🔹 1. Understanding HTML & How the Web Works
- What HTML is  
- Browser rendering basics  
- Relationship between HTML, CSS, JS  
- File structure & creating your first `.html` file  

### 🔹 2. The HTML Document Structure
Tags you will fully understand:
- `<!DOCTYPE html>`
- `<html>`
- `<head>`
  - `<title>`
  - `<meta charset="UTF-8">`
  - `<meta name="viewport">`
  - `<meta name="description">`
  - `<link>`, `<style>`, `<script>`
- `<body>`

### 🔹 3. Text & Content Elements
- Headings: `h1` to `h6`
- Paragraphs: `p`
- Line breaks: `br`
- Horizontal line: `hr`
- Comments: `<!-- comment -->`
- HTML entities: `&nbsp;`, `&copy;`, `&#169;`, …etc

### 🔹 4. Block vs Inline Elements
**Block examples:** `div`, `section`, `article`, `header`, `footer`, `main`  
**Inline examples:** `span`, `a`, `strong`, `em`, `img`

### 🔹 5. Core Attributes (Important!)
- `id`, `class`
- `src`, `href`, `alt`, `target`
- `title`
- `style`
- Boolean attributes: `disabled`, `checked`, `required`

### 🔹 6. Links & Navigation
- `a href=""` (internal & external)
- Anchor links (`#section`)
- Best practices for navigation

### 🔹 7. Media Elements
- Images: `<img>`
- Audio: `<audio controls>`
- Video: `<video controls>`
- Source element `<source>`
- File formats & compatibility

**Hands-on practice:**
- Build a basic webpage with text, images, metadata, and navigation
- Correctly use headings and structure
- Add audio/video components

---

## Session 2 — Semantic HTML, Lists, Tables, Forms & Final Project (3 Hours)

**What you will learn:**

### 🔹 1. Semantic HTML (VERY Important)
Understand the purpose and usage of:
- `header`
- `nav`
- `main`
- `section`
- `article`
- `aside`
- `footer`
- `figure`, `figcaption`
- `time`
- `mark`
- `address`

### 🔹 2. Lists
- Unordered lists: `<ul>`
- Ordered lists: `<ol>`
- List items: `<li>`
- Nested lists
- Navigation menus using lists

### 🔹 3. Tables (Full Coverage)
Tags included:
- `<table>`
- `<thead>`
- `<tbody>`
- `<tfoot>`
- `<tr>`
- `<th>`
- `<td>`
- `<caption>`
- Attributes: `colspan`, `rowspan`
- When to use tables (and when NOT to)

### 🔹 4. Forms (Complete)
You will learn:
- `<form>`
- `<label>`
- `<input>`
- `<textarea>`
- `<select>`, `<option>`
- `<button>`
- Input types:
  - `text`, `email`, `password`, `tel`, `number`
  - `checkbox`, `radio`
  - `date`, `file`, `range`, `color`
- Validation basics:
  - `required`
  - `min`, `max`
  - `maxlength`
  - `pattern` (regex)

### 🔹 5. Accessibility & SEO Basics
- Proper use of labels  
- Alt text guidelines  
- Semantic structure for screen readers  
- Avoiding incorrect heading order  
- Metadata for SEO  
- ARIA introduction (very short)

### 🔹 6. Best Practices
- Avoid overusing `<div>` ("div soup")  
- Use semantic tags whenever possible  
- Clean indentation  
- Meaningful class names  
- Proper HTML comments  
- Avoid inline styling

---

## Final Mini Project (at the end of Session 2)

Build a complete, fully structured landing page that includes:

### It must contain:
- `header` with navigation  
- `main` with multiple sections  
- Hero section (title + text + image)  
- Features section (using lists or semantic tags)  
- A styled table  
- A full contact form  
- `footer` with copyright info  
- At least 1 image and 1 video/audio  
- Proper metadata inside `<head>`  

### Key goals:
- Perfect semantic structure  
- Clean and readable HTML  
- Accessibility-friendly  
- SEO-ready structure  
- No CSS needed yet — pure HTML layout  

This final project fully prepares you for the CSS roadmap.

---


## 🎨 CSS Roadmap (10 Hours — 5 Sessions × 2h)  
**+ 1 Framework Session (Tailwind or Bootstrap)**  
**+ Optional Sass Session**

**Overview:**  
This CSS roadmap covers everything you need before starting JavaScript, React, and TypeScript.  
You will learn the fundamentals, advanced layout systems, responsive design, and modern UI utilities.  
Total: **5 core CSS sessions** + **1 framework session**.

---

### Session 1 — CSS Basics & Selectors (2h)
**Topics:**
- Linking CSS to HTML (external, internal, inline)
- Basic selectors (element, class, id)
- Combining selectors
- Colors, backgrounds, opacity
- Box Model (content, padding, border, margin)
- Display types (block, inline, inline-block, none)

**Practice:**
- Style a basic webpage with headings, paragraphs, images, background colors, and spacing.

---

### Session 2 — Units, Positioning & Layout Foundations (2h)
**Topics:**
- CSS Units: `px`, `%`, `em`, `rem`, `vh`, `vw`
- `box-sizing: border-box`
- Positioning: `static`, `relative`, `absolute`, `fixed`, `sticky`
- z-index explained
- Overflow (hidden, scroll, auto)

**Practice:**
- Build a styled card with positioned elements (badge, overlay, absolute elements).

---

### Session 3 — Typography, Selectors & Visual Design (2h)
**Topics:**
- Font properties: family, size, weight, line-height
- Loading fonts (Google Fonts)
- Advanced selectors:
  - Attribute selectors
  - Pseudo-classes (`:hover`, `:focus`, `:active`)
  - Pseudo-elements (`::before`, `::after`)
- CSS Specificity, Cascade & Inheritance

**Practice:**
- Style a hero section with custom fonts and decorative pseudo-elements.

---

### Session 4 — Flexbox Deep Dive (2h)
**Topics:**
- Main axis vs cross axis
- Container properties:
  - `display: flex`
  - `flex-direction`
  - `flex-wrap`
  - `justify-content`
  - `align-items`
  - `gap`
- Item properties:
  - `flex-grow`
  - `flex-shrink`
  - `flex-basis`
  - `order`
- When to use Flexbox

**Practice:**
- Build a responsive navbar + responsive card layout using Flexbox.

---

### Session 5 — CSS Grid & Responsive Design (2h)
**Topics:**
- Grid setup: `grid-template-columns`, rows, areas
- `gap`, implicit vs explicit grids
- Grid vs Flexbox (which to use?)
- Responsive design:
  - Mobile-first approach
  - Media queries (`min-width`, `max-width`)
  - Responsive typography
  - Responsive images (`srcset`, `picture`)

**Practice:**
- Build a multi-section layout (header, sidebar, main, footer)  
- Add responsiveness for mobile, tablet, desktop.

---

### Session 6 — Framework Session (Choose One) (2h)
**Option A — Tailwind CSS**
- Utility-first workflow  
- Responsive classes  
- Hover/Active/Focus states  
- Building UI fast with utility classes  

**Option B — Bootstrap**
- Bootstrap Grid system  
- Containers, rows, columns  
- Common components (navbar, cards, buttons)  
- Utility classes  

**Practice:**
- Rebuild a section of your page using Tailwind or Bootstrap.

---

### Bonus (Optional) — Session 7: Sass (2h)
**Topics:**
- What is Sass and why use it?
- Variables
- Nesting
- Partials and file structure
- Mixins
- Functions
- Compiling Sass (CLI / VSCode extension)

**Practice:**
- Convert your CSS project into a structured Sass project.

---

##  What You Will Achieve
- Full understanding of modern CSS fundamentals  
- Ability to build clean and responsive layouts  
- Confidence using Flexbox & Grid  
- Experience with Tailwind or Bootstrap  
- A solid base before starting JavaScript, React, and TypeScript  

---

## Final Project — Complete Responsive Website

**Goal:**  
Build a fully responsive, visually polished multi-section website using everything learned in the CSS roadmap.

**Your final project must include:**
- **Header** with navigation  
- **Hero section** with typography and buttons  
- **Features section** (Grid or Flexbox)  
- **Image/content section**  
- **Contact form**  
- **Footer**  
- **Mobile, tablet, and desktop breakpoints**  
- **At least 2 CSS animations or transitions**  
- **Clean and organized CSS structure**

**Optional enhancements:**
- Rebuild the same project using **Tailwind or Bootstrap**  
- Convert the project into **Sass** for cleaner structure

This project becomes your first real portfolio piece on GitHub.

---

## ⚡ JavaScript Roadmap (12 Hours — 6 Intensive Sessions × 2h)

**Overview:**  
This roadmap is a highly condensed, intensive JavaScript learning track designed to prepare you quickly and efficiently for React, TypeScript, and modern frontend development.  
You will cover language fundamentals, DOM, asynchronous JS, the event loop, APIs, modules, and advanced concepts — all in just 6 powerful sessions.

---

### 🕒 Session 1 — JS Fundamentals & Execution Model (2h)
**Topics:**
- What JavaScript is & how it runs in the browser  
- JS Engine (V8), Memory Heap, Call Stack  
- Execution Context (Creation / Execution phases)  
- Hoisting (variables & functions)  
- Variables: `var`, `let`, `const`  
- Primitive vs Reference types  
- Operators & conditionals (`if`, `switch`, logical operators)  
- Functions:
  - Declarations vs expressions  
  - Arrow functions  
  - Parameters vs arguments

**Practice:**
- Small utilities (calculator, string manipulations)  
- Logging execution order to understand stack behavior  

---

### 🕒 Session 2 — Arrays, Objects, ES6 & DOM Intro (2h)
**Topics:**
- Arrays: `map`, `filter`, `reduce`, `find`, `forEach`  
- Objects: keys, values, methods, destructuring  
- Spread & Rest operators  
- Template literals  
- DOM manipulation:
  - Selecting elements  
  - Changing text, HTML & styles  
  - Creating & removing elements  
- Event handling: click, input, submit

**Practice:**
- Build a dynamic counter  
- Build a simple Todo List (DOM + events)

---

### 🕒 Session 3 — The Event Loop, Web APIs & Asynchronous JS (2h)
**Topics:**
- Sync vs Async  
- **Call Stack**  
- **Web APIs**  
- **Callback Queue**  
- **Microtask Queue**  
- **Event Loop**  
- Callback functions  
- Callback Hell  

**Practice:**
- Asynchronous examples using `setTimeout`  
- Visualize Event Loop behavior  
- Create a loading simulation or delayed UI update

---

### 🕒 Session 4 — Promises, Async/Await & Fetch API (2h)
**Topics:**
- Promise states  
- `.then()`, `.catch()`, `.finally()`  
- `async` / `await`  
- Handling promise errors  
- Fetch API (GET, POST)  
- JSON: `JSON.stringify` & `JSON.parse`  
- Handling real APIs  
- Common API errors & how to avoid them

**Practice:**
- Fetch and display data (Users, Products, Weather…)
- Build a search UI with API requests  

---

### 🕒 Session 5 — Modules, OOP & Advanced JS Concepts (2h)
**Topics:**
- ES Modules (`import`, `export`)  
- Named vs default exports  
- OOP in JavaScript:
  - Constructor functions  
  - Prototypes  
  - Classes & Inheritance  
- `this` keyword (regular functions vs arrow functions)  
- `.bind()`, `.call()`, `.apply()`  
- Closures  
- IIFE (Immediately Invoked Functions)

**Practice:**
- Build a class-based component (User, Product…)  
- Convert a small JS app into ES Module structure

---

### 🕒 Session 6 — Browser APIs, Storage & Final JS Project (2h)
**Topics:**
- LocalStorage  
- SessionStorage  
- Timers (`setTimeout`, `setInterval`)  
- Clipboard API  
- Geolocation API  
- Form validation  
- Error handling:
  - try/catch  
  - Custom errors  

**Final Project Requirements:**
Build a complete JavaScript application that includes:
- DOM manipulation  
- API fetching  
- Async/await  
- Events  
- LocalStorage  
- Modules (optional but recommended)  
- Clean folder structure  

**Suggested projects:**
- Weather App  
- GitHub User Search  
- Notes App  
- Movie Search App  

---

## 🎯 What You Will Achieve
- A compact but powerful understanding of core JavaScript  
- Ability to build real, interactive apps  
- Deep understanding of the Event Loop, Web APIs & async behavior  
- Strong readiness for React, TypeScript & modern frontend frameworks  



## ⚛️ React.js Roadmap (8 Hours — 4 Intensive Sessions × 2h)

**Overview:**  
A fast and efficient React roadmap built to prepare you for real projects, TypeScript, and modern frontend frameworks.  
You will learn components, hooks, state management, props, events, routing, API fetching, and project structure — all in 4 focused sessions.

---

### 🕒 Session 1 — React Fundamentals & Component System (2h)
**Topics:**
- What is React? Why React is popular  
- SPA (Single Page Applications)  
- How React works (Virtual DOM, Reconciliation, Rendering)  
- Create React App vs Vite  
- JSX basics  
- Components:
  - Function components  
  - Props  
  - Children props  
  - Conditional rendering  
  - Lists & keys  

**Practice:**
- Create a component-based layout (Navbar, Hero, Footer)  
- Build a reusable Card component with props  

---

### 🕒 Session 2 — State, Events & Essential Hooks (2h)
**Topics:**
- State with `useState`  
- Event handling  
- Controlled vs uncontrolled components  
- Forms in React  
- `useEffect`:
  - Side effects  
  - Dependency array  
  - Cleanup  
- Rendering behavior (when React re-renders & why)

**Practice:**
- Build a dynamic counter with `useState`  
- Build a form with validation using controlled inputs  
- Use `useEffect` to sync values or detect changes  

---

### 🕒 Session 3 — Fetching Data, Routing & Global State Basics (2h)
**Topics:**
- Fetching data with Fetch API  
- Async/await inside React components  
- Loading / error states  
- React Router:
  - Routes  
  - Links  
  - useParams  
- Lifting state up  
- Prop drilling problem  
- Context API (global state without Redux)

**Practice:**
- Build a Users List page (fetching API + loading state)  
- Build a user details page with React Router  
- Use Context API for theme toggle or auth-like state  

---

### 🕒 Session 4 — Project Structure, Advanced Patterns & Final Mini Project (2h)
**Topics:**
- Project folder structure (components, pages, hooks, services)  
- Custom Hooks:
  - Extracting logic  
  - Reusability  
- Performance basics:
  - `React.memo`  
  - `useCallback`  
  - `useMemo`  
- Error boundaries (intro)  
- Best practices for clean React code  
- Preparing for Next.js and TypeScript  

**Final Mini Project (Choose One):**
- **Weather App** (API + components + routing)  
- **Movie Search App** (API + search input + results page)  
- **GitHub Users Explorer** (routing + API + dynamic pages)  
- **Notes App** (localStorage + custom hooks + components)

**Project must include:**
- State management  
- API fetching  
- React Router  
- Clean reusable components  
- Custom hooks (at least one)  
- Error & loading handling  
- Responsive layout  

---

## 🎯 What You Will Achieve
- Solid understanding of React’s core concepts  
- Ability to build real SPA applications  
- Confidence with hooks, routing, and API calls  
- A clean coding style ready for TypeScript and Next.js  
- A final React project ready for your portfolio  

## ▲ Next.js + TypeScript Roadmap (4 Sessions × 2h)  
### **+ 2 Final Project Sessions**  
_Total: 12 Hours_

**Overview:**  
This track teaches you how to build modern, fast, SEO-friendly applications using **Next.js** with **TypeScript**.  
You'll learn routing, data fetching, dynamic pages, APIs, server components, file structure, and deployment — all in a short, focused roadmap.

---

## ▲ Next.js + TypeScript Roadmap (4 Sessions × 3h)

**Overview:**  
A highly intensive roadmap combining Next.js + TypeScript + a real-world final project.  
The goal is to prepare you for modern frontend development using server components, routing, API routes, data fetching, and TypeScript best practices.

Total: **4 sessions**  
- **2 sessions Next.js**
- **1 session TypeScript**
- **1 final full project session**

---

## 🕒 Session 1 — Next.js Fundamentals (3 Hours)

### 🔹 What you will learn:
- What is Next.js? Why use it instead of React alone?  
- How Next.js works (Server Components, Client Components)  
- Project setup with Next.js 13/14 App Router  
- File-based routing  
- The `app/` directory  
- `layout.tsx` and shared UI  
- Metadata & SEO basics  
- Creating pages:  
  - `app/page.tsx`  
  - `app/about/page.tsx`  
- Navigation with `Link`  
- Static vs Dynamic rendering overview  
- Assets & Image optimization (`next/image`)  
- Fonts optimization (`next/font`)  

### 🔹 Practice:
- Create a small multi-page structure (Home, About, Contact)  
- Add metadata to each page  
- Add an optimized image & custom Google font  

---

## 🕒 Session 2 — Data Fetching, APIs, Routing & Server Logic (3 Hours)

### 🔹 Data fetching (core of Next.js)
- Server Components fetch  
- Automatic caching  
- `cache: 'no-store'`  
- Revalidation (`revalidate: 10`)  
- Dynamic fetch with params  

### 🔹 Dynamic routing
- `[id]` routes  
- `generateStaticParams`  
- Nested routes  
- Loading & error UI  
  - `loading.tsx`  
  - `error.tsx`

### 🔹 API Routes
- Creating API endpoints:  
  - `/app/api/users/route.ts`  
- Handling POST/GET  
- Returning JSON responses  
- Using fetch to call your own APIs  
- Env variables (`process.env.API_KEY`)

### 🔹 Forms & Server Actions
- Creating forms in Next.js  
- Handling form submissions on the server  
- Intro to server actions (Next.js 14)

### 🔹 Practice:
- Build a dynamic route: `/users/[id]`  
- Fetch data and show loading/error UI  
- Create an API route `/api/message`  
- Add a form that sends data to an API route  

---

## 🕒 Session 3 — TypeScript for React & Next.js (3 Hours)

### 🔹 TypeScript Essentials
- Types vs Interfaces  
- Type inference  
- Union & intersection types  
- Literal types  
- Optional & readonly  

### 🔹 TypeScript with React Components
- Typing props  
- Typing children  
- Typing events (mouse, input, form)  
- Typing state (`useState<number | null>`)  
- Typing custom hooks  
- Typing async functions  
- Typing API responses (DTOs)  

### 🔹 TypeScript with Next.js
- Typing `params` in dynamic routes  
- Typing API route handlers  
- Typing Server Components & Client Components  
- Error handling with TS  
- Writing reusable types  

### 🔹 Practice:
- Convert a full page to TypeScript  
- Type route params  
- Type API response & fetch logic  
- Build a typed custom hook: `useUsers()`  

---

## 🕒 Session 4 — Final Project (3 Hours)

### 🎯 Goal:
Build a **complete, production-ready Next.js + TypeScript application** using everything learned.

### Your final project must include:

#### 🔹 Required features:
- Next.js App Router  
- Server Components + Client Components  
- Dynamic routes: `/items/[id]`  
- Fetching real API data  
- A working API route (GET + POST)  
- Form submission (client or server action)  
- Error & Loading UI  
- TypeScript everywhere  
- Clean folder structure  
- Fully responsive design  
- Deployment on Vercel

#### 🔹 Suggested project ideas:
- **E-Commerce Product Explorer**  
  - Listing products  
  - Product details (dynamic route)  
  - Cart stored in localStorage  
  - Search + filter  

- **Blog Platform**  
  - Dynamic blog posts  
  - Markdown MDX support  
  - Comments API  

- **GitHub User Explorer**  
  - Search users  
  - Dynamic user pages  
  - Repos, followers  

- **Recipe App**  
  - Recipe listing  
  - Dynamic details page  
  - Add new recipe form  

### 🔹 Final Delivery:
- GitHub repository with clean code  
- Deployed project on Vercel  
- Added to portfolio  
