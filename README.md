# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug: an infinite loop caused by an improperly used `useEffect` hook.  The `useEffect` hook, without a proper dependency array, will re-render the component endlessly.