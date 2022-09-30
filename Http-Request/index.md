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
