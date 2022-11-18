# psflk_nextjs_test

1. React is built in
2. Routing is handeled automatically, by adding a file into posts, it creates a directory
3. Lazy loading for images is optimized automatically by using built in React components
4. Links are client-rendered when using the Link-Tag instead of the default a-Tag
5. The head can be easily accessed by the use of Head-Tag (for instance to modify the title of the page)
6. Load external scripts with Script-Tag (and attributes such as strategy="lazyOnLoad" and onLoad={() => someFunction})
7. Use css modules to avoid css class-name collisions
8. Next.js also supports global css files
9. Using classnames library to toggle classes
10. Pre-rendering is done by next.js on default
11. Dynamic routes with [] under pages