<script>
    export let pokeman ;
</script>

<div class="flex items-center">
    <div class=" bg-white m-2 p-8 rounded">
     <a href={`/pokeman/${pokeman.id}`}> 
<img class="w-32 h-32" src={pokeman.image} alt={pokeman.name}>
<h2>{pokeman.id}.{pokeman.name}</h2>
</a>   
    </div>


</div>
