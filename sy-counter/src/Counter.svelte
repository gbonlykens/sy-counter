<script>
    let count = 0;
  
    function handleClick() {
      count += 1;
    }
  </script>
  
  <button 
   on:click={handleClick}>
    Ouch! You have poked me {count}
    {count === 1 ? "time" : "times"}
  </button>