# React: Memory Leak in setInterval useEffect Hook

This repository demonstrates a common React bug involving memory leaks due to the misuse of the `setInterval` function within the `useEffect` hook.  The provided code sets up an interval to increment a counter but fails to properly clear the interval, causing a memory leak.

The solution demonstrates how to correctly clear the interval when the component unmounts, preventing memory leaks.