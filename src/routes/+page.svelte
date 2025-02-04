<script>
    let message = "meow meow";
</script>
 
<div> 
    <h1>{message}</h1>
    <p>Write whatever you want:</p>
    <input type="text" bind:value={message}/>
</div>
<style>
input[type="text"] {
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 10px;
    font-size: 16px;
    border: 2px solid #ddd;
    border-radius: 4px;
    width: 300px;
    margin-top: 10px;
}

h1 {
    font-size: 36px;
    color: #333;
    margin-bottom: 20px;
}

p {
    font-size: 18px;
    color: #555;
}
</style>