<script>
  let count = 0;
  let str = `tou have clicked ${count}`;
  const increment = () => {
    count += 1
}
$:str = `you have clicked ${count}`;
</script>
 
<button on:click={increment}>
  count is {count}
</button> 
<h2>{str}</h2>
 