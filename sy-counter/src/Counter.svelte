<script>
    let numberOfClicks = 0;
  
    function handleClick() {
      numberOfClicks += 1;
    }
  </script>
  
  <button 
   on:click={handleClick}>
    Ouch! You have poked me {numberOfClicks}
    {numberOfClicks === 1 ? "time" : "times"}
  </button>

  <style>
    button {
      display: inline;
      justify-content: center;
      align-items: center;
      padding: 15px;
      margin-left: 510px;
      background-color: #FA8072;
      border-radius: 25px;
    }
    button:hover {
      cursor: pointer;
    }
  </style>