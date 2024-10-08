<script>
    async function login(){
        alert('Botão login apertado!')
    }

    // const response = await fetch('/todo', {
	// 		method: 'POST',
	// 		body: JSON.stringify({ description }),
	// 		headers: {
	// 			'Content-Type': 'application/json'
	// 		}
	// 	});
</script>

<h2>Login</h2>
<hr>

<div class="d-flex flex-column p-3 form-div col-md-6 col-lg-4 col-sm-8">
    <div class="mb-2">
       
        <label for="email" class="form-label">Email:</label>
        <input type="email" id="email" class="form-control">
    </div>
    <div class="mb-2">
        <label for="password" class="form-label">Password:</label>
        <input type="password" id="password" class="form-control">
    </div>
    <div class="my-4">
        <button class="btn btn-primary" on:click={login}>Login</button>
    </div>
</div>

<style>
    .form-div{
        background-color: #062593;
        border-radius: 10px;
    }
</style>
