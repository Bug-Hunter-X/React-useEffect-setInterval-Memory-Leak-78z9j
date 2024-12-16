# React useEffect setInterval Memory Leak

This repository demonstrates a common error in React applications involving the `useEffect` hook and the `setInterval` function.  Improperly using `setInterval` within `useEffect` without a cleanup function leads to memory leaks as the interval continues running even after the component unmounts. The solution showcases how to fix this issue.