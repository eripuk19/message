<script>    
// Set the initial message to "meow meow"
let message = "meow meow";
</script>
 
<div> 
    <!-- Show the message in a heading -->
    <h1>{message}</h1>
    <!-- Ask the user to write something -->
    <p>Write whatever you want:</p>
    <!-- Input field where the message can be changed -->
    <input type="text" bind:value={message}/>
</div>

<style>
/* Style the input field */
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

/* Style the heading */
h1 {
    font-size: 36px;
    color: #333;
    margin-bottom: 20px;
}

/* Style the paragraph */
p {
    font-size: 18px;
    color: #555;
}
</style>