# React 19 useEffect Cleanup Issue

This repository demonstrates a common issue encountered in React 19 where the cleanup function within a `useEffect` hook is not called when the component unmounts. The problem is often related to missing dependencies or other lifecycle management issues. 

## Bug Description
The `useEffect` hook's cleanup function is crucial for tasks such as clearing intervals, unsubscribing from events, or releasing resources.  In this example, the cleanup function should log 'Component unmounted' when the component is unmounted, but this is not happening consistently.