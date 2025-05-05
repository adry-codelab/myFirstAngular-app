# FirstNgApp

# 📘 My Angular Learning Summary

This repository contains my personal notes from learning Angular, the popular front-end framework developed by Google for building Single Page Applications (SPAs).

## 🚀 What I Learned

### ✅ Fundamentals of Angular

- Angular is a powerful SPA framework with built-in tools like routing, HTTP services, and form handling.
- Developed and maintained by Google, supported by a strong developer community.

### 🔄 Data Binding

- Learned both traditional data binding and the new **Signals-based** reactive approach.
- Explored two-way data binding, event handling, and DOM interaction.

### 📦 Component Communication

- Used `@Input()` to pass data from parent to child components.
- Handled DOM events using template syntax and event objects.

### 🧭 Routing and Lazy Loading

- Implemented Angular routing to define SPA navigation.
- Used lazy-loaded components for better performance.

### 🌐 HTTP and Services

- Created services to encapsulate business logic.
- Used `HttpClient` to fetch data from APIs and inject services into components.

### 🧰 Directives and Pipes

- Used built-in and custom **attribute and structural directives**.
- Learned how to transform data using Angular **pipes** in templates.

### 🧪 Testing Angular Apps

- Learned basics of unit testing with **Jest** and end-to-end testing with **Cypress**.

### ⚡ Performance and Optimization

- Applied best practices like lazy loading, OnPush change detection, and efficient RxJS usage.

### 📱 Building PWAs

- Explored how to turn Angular apps into installable Progressive Web Apps using `@angular/pwa`.

### 🧠 Additional Concepts

- Reactive state management using **NgRx**
- Animation support
- Angular CDK utilities

## 🧠 Resources Used

- [ng-cookbook.com](http://ng-cookbook.com/)
- Angular official documentation
- Personal experiments and practice projects

---

🛠 This repo is my personal Angular learning tracker and reference guide. Feel free to explore or fork it for your own learning!

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
