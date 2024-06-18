# React + Vite + TanStack => Infinite Scroll

This template provides a exercise of Infinite Scroll of React Query:
React Query manages:
1. pageParam - for next page to be fetched
- getNextPageParam option
- could be from last page, or all pages
2. HasNextPage
-boolean indicating whether pageParam is undefined
3. Component handles calling fetchNextPage
- use hasNextPage property value to determine when to stop
