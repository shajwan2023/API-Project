<script>
import PokemonCard from "../components/pokemonCard.svelte";
import {pokemon ,fetchPokemon} from  "../stores/pokestore"
//    console.log($fetchPokemon)
 fetchPokemon()
 let searchTearm ="";
 let filterPokemon =[];
</script>



 <div class="bg-slate-300 p-10">
<div class="max-w-screen-2xl mx-auto">
   
   <input placeholder="search pokemon" type="text" name="" id="" class=""  bind:value={searchTearm}>

 <div class="grid grid-cols-8">
{#each $pokemon as pokeman}
<PokemonCard pokeman={pokeman} />
{/each}
 </div>
</div>
 </div>


