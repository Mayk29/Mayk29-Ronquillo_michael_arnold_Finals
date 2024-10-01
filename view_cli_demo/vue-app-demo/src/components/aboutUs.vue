<template id="about">
    <div id="about-us">
        <div id="todo-card">
            <div class="container">
                <div class="alert alert-primary" role="alert">
                    <h1>{{ msg6 }}</h1>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default{
    name:"about-us",
    data (){
        return{
            msg6:'Creating SPA'
        }
    }
}
</script>

<style>
#about{
    background-color: #e6f7ff;
}

h1{
    color: #fff;
    text-align: center;
}

</style>
