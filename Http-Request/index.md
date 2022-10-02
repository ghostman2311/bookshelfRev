# Promises

1. fetchPokemon('pikachu').then(pokemonData => {
   setPokemon(pokemonData)
   }, error => {
   setError(error)
   })

2. fetchPokemon('pikachu').then(pokemonData => {
   setPokemon(pokemonData)
   }).catch(error => {
   setError(error)
   })

- What is the difference between above two?

# Error Boundaries

1. How to create getDerivedStateFromError()? When does it run ?
2. How to render children if there is no error in ErrorBoundary?
3. How to Fallback component to Our custom ErrorBoundary?
4. How to reset the internal state of error boundary?
5. What are the disadvantage of using above technique inside our application?
6. What is second argument of errorFallback function?
