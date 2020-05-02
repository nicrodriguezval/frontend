<template>
    <div class="container p-4">
        <div class="row">
            <div class="col -md-3">
                <div class="card animated flipInY">
                    <div class="card-header bg-primary text-white text-center">
                        <h3>
                            Log in
                        </h3>
                    </div>
                    <div class="card-body">
                        <form method="post">
                            <div class="form-group">
                                <label for="inputEmail">Email address</label>
                                <input name="email" id="inputEmail" type="email" class="form-control" placeholder="Email" required>
                            </div>
                            <div class="form-group">
                                <label for="inputPassword">Password</label>
                                <input type="password" class="form-control" id="inputPassword" placeholder="Password" name="password" required>
                            </div>
                            <div class="form-group">
                                <br>
                                <div style="text-align: center">
                                    <input type="submit" value="Submit" class="btn btn-primary">
                                    <input type="button" value="Go Back" onclick="history.back()" class="btn btn-primary">
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>        
    </div> 
</template>

<script>
export default {

}
</script>

<style>

</style>