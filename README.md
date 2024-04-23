# nextjs-example
- react v18.2.0

## Chapter
- https://nextjs.org/learn/dashboard-app/navigating-between-pages
- https://nextjs.org/learn/dashboard-app/setting-up-your-database
  - Postgres database. 
  ```
  npm i @vercel/postgres
  ```
- https://nextjs.org/learn/dashboard-app/fetching-data
  - useEffect, useState (async/await)
- https://nextjs.org/learn/dashboard-app/static-and-dynamic-rendering
  - Faster Websites, Reduced Server Load, SEO
  - Real-Time Data, User-Specific Content, Request Time Information
- Streaming(https://nextjs.org/learn/dashboard-app/streaming)
  - Suspense (https://react-ko.dev/reference/react/Suspense)
  - https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming
- Partial Prerendering (Optional) (https://nextjs.org/learn/dashboard-app/partial-prerendering)
  - static area, dynamic area
- Adding Search and Pagination (https://nextjs.org/learn/dashboard-app/adding-search-and-pagination)
  - APIs: searchParams, usePathname, useRouter
  
  ```
  npm i use-debounce
  (https://www.npmjs.com/package/use-debounce)
  ```

- Mutating Data (https://nextjs.org/learn/dashboard-app/mutating-data)
- Handling Errors (https://nextjs.org/learn/dashboard-app/error-handling)
  - 강제 에러 발생 throw new Error("메세지");
  - try/catch (java와 동일)
  ```
  try {
    ...
  } catch(error) {
    return { message: 'message'};
  }
  ```
  - custom Erorr관련 표기를 위해서는 각 페이지의 루트 경로에 error.tsx 추가 필요 (error.js next.js 내장 API)
  - 404같은 공용 에러는 각 페이지 경로에 xxx.tsx(ex. not-found.tsx) 추가 필요 (notFound(), not-found.js next.js 내장 API)

- Improving Accessibility (https://nextjs.org/learn/dashboard-app/improving-accessibility)
  - eslint-plugin-jsx-a11y
  ```
  npm i eslint-plugin-jsx-a11y
  ```
  - todo: 이어서 확인 필요



## create project
  - https://nextjs.org/docs/pages/api-reference/create-next-app

## build
  - https://www.moonkorea.dev/React-NextJS-%EB%B9%8C%EB%93%9C-%EB%A6%AC%EC%86%8C%EC%8A%A4-%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0#%EB%B9%8C%EB%93%9C
 
## ref
  - https://nextjs.org/
  - https://tailwindcss.com/
  - https://woodaelog.com/31.NextJs-basic-grammer/
  - https://github.com/grotesq/Codelab-Next-JS-2nd/blob/master/_documents/1%EA%B0%95%20-%20Next.js%EC%9D%98%20LifeCycle.md
