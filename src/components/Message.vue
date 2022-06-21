<template>
  <div class="message-container">
    <p><i class="fa fa-check-circle-o" aria-hidden="true"></i>
 {{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: "Message",
  props: {
    msg: String
  }
}

</script>

<style scoped>
  .message-container {
    /* border: 1px solid rgba(36, 241, 6, 0.46); */
    /* background-color: rgba(7, 149, 66, 0.12156862745098039); */
    /* box-shadow: 0px 0px 2px #259c08; */
    /* color: #0ad406; */
    
    transition:0.5s;
    cursor:pointer;

    color: #004085; 
    background-color: #CCE5FF;
    border: #B8DAFF;
    border-radius: 5px;
    padding: 10px;
    max-width: 400px;
    margin: 30px auto;
  }
</style>