# React Performance

## Code Splitting

1. How to lazy load a component?
2. Why we are providing fllabck components to suspense?
3. How to eager loading the components using event handlers?
4. What are webpack magic comments ?
5. Where to put suspense?

## useMemo for expensive calculations

1. How to analyze which function is taking so long in performance tab.
2. How to pass a function in useMemo
3. What is webworker?
4. How to use useAsync in place of react memo

## React.memo for reducing unnecessary re-renders

1. What is the lifecycle of react app?
2. What is the second argument of react.memo?
3. What if we return true in second argument of react.memo

## Optimizing context value

1. What are we trying to fixup here? Please simulate it first.
2. The two most expensive components are Grid and Cell, But we are already memoizing them then what is main problem that every item is re-rendering.
3. Why is context value changes for every re-render?
4. What is deep and shallow comparison?
5. Simulate deep and shallow copy.
6. What is the problem we are trying to solve in extra credit?

## Web worker

1. Web worker does not have access to the DOM. so no window or document.
