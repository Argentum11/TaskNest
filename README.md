# TaskNest

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.0.0 and is part of the **[Angular - The Complete Guide (2024 Edition)](https://www.udemy.com/course/the-complete-guide-to-angular-2)**.

## Development server

Run `ng serve` for a dev server. Navigate to [http://localhost:4200/](http://localhost:4200/). The application will automatically reload if you change any of the source files.

## learning goals

- Build options
  - SPA (Single Page Application)
    - Client-side only web application
    - Requires a static host (e.g., Firebase-Hosting, GitHub Pages)
    - Cons
      - Initially missing content (UI is rendered by Javascript)
      - Poor SEO (search engines aren't guaranteed to wait for the UI rendering)
    - Use cases
      - Internal application
      - An application that always require authentication
  - SSR (Server Side Render)
    - Server receives requests from the client and returns rendered pages
    - Web app is hydrated and becomes a SPA after initial rendering
    - Requires a dynamic web server
    - Pros
      - great for SEO
    - Cons
      - Complexity
      - Long taking tasks may cause empty pages
    - Implementation steps
      1. `ng add @angular/ssr`
      2. `npm run build`
    - warning
      - local storage related code needs to be modified
