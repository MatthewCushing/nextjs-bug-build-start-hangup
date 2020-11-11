# NextJS Production Build Bug

1. `npx create-next-app myAppName`
2. `cd myAppName`
3. `npm run build`
4. `npm run start`
5. Go to http://localhost:3000 in the browser and the browser hangs with this error:
```bash
TypeError: Object(...) is not a function
    at t.default (_app-79ac36cb280f51a22a9b.js:1)
    at no (framework.4ed712e956e4440973f2.js:1)
    at ju (framework.4ed712e956e4440973f2.js:1)
    at xi (framework.4ed712e956e4440973f2.js:1)
    at Si (framework.4ed712e956e4440973f2.js:1)
    at ki (framework.4ed712e956e4440973f2.js:1)
    at pi (framework.4ed712e956e4440973f2.js:1)
    at framework.4ed712e956e4440973f2.js:1
    at t.unstable_runWithPriority (framework.4ed712e956e4440973f2.js:1)
    at jl (framework.4ed712e956e4440973f2.js:1)
```
