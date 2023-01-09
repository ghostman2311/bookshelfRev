# Dynamically fetching and Loading of npm modules

## Resolving nested paths

1. Now we have problem with loading of 'nested-test-pkg', because everything is inside src folder unpkg redirect to us different link. Now illustrate how can we use of new URL and resolve Dir to solve this problem.

## Defines During bundling

1. How to import react?
2. How to define process.env.NODE_ENV and global in application?

# Caching for Big Performance gain

## Implementing a caching layer

1. Why are even going for caching?
2. What storage we are going to use for caching?
3. Which package we are going to use as helper library

# Safely handling untrusted code execution

## Executing User Code

1. What is eval function?
2. What happen if we enter console.lsada('sadasd') function, How do we solve this?
3. If we use setTimeOut then call above function then what happens?

## Big issues with code execution

1. How user can mutate the dom with code, Give an example
2. What are the three problems while executing the users code.

## How do others solve this

1. Which HTML element major websites are using?

## Displaying IFRAMES

1. Create test.html in public folder.
2. Now Display the test.html in an iframe.

## Different Execution Context

1. What are parent and child context. Give the description.

## Crossing Context

1. Access the parent property in child.
2. Access the child property in parent.
3. contentWindow is a property that we are using.

## Sandboxing an Iframe

1. How can we use sandbox property to disable the connection.

## Breaking access with different domains

1. What is the second property to have direct connection between parent and child

## How do Iframes fix anything

1. How codesandbxo and codepen is breaking the connection as they have enable "allowed-same-origin" property.

## The Full flow, How codesandbox and codepen works

1. What is full flow codepen.io

## Do we need separation

1. Understand the code pen flow.

## Middle Ground Approach

1. When Direct access is allowed, write out the condition.
2. Which approach we are going to use.
3. What is downside of this approach.
