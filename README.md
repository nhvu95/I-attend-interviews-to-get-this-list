# I attend interviews to get this list

This is the list of questions I got in the interview. Don't ask me the answer because I fail a lot :cry:. Ask GPT yourself

## FRONTEND

1. How a browser load a page and display to the user? (explain from browser get index.html until it display everything)
2. How a browser handle a <script> tag?
3. Explain closure. (Actually he give me a srcript then ask me exlain)
4. How to make a private property in js?
5. What is prototype? Different betweeen prototype and __proto__
6. Given a script. Give me the output order.
```javascript
  setTimeout(() => {
    console.log("b");
  });
  const promise = new Promise((resolve) => resolve("c"));
  promise.then(res => console.log(res));
  console.log("a");
```
7. Explain the different between localStorage, sessionStorage, Cookie?
8. Do you know PWA?
9. Do you know why JS is single thread?
10. What is tree shaking in webpack.
11. In one way binding or two way binding, How system know that a (property) variable is change then do update the screen?
12. Where do you store access-token?
13. What is best practice to manage token in the frontend side.
14. localStorage will share the token with the sub domain. Some people don't want to do that, they want only some sub domain can view the token and some domain cannot. How will you do?
15. When Angular, React, Vue detech a change, Do they render all that component, or only the change html element?
16. What is throttling, debouncing?
