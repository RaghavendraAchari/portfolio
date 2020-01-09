<template>
    <div>
        <div class="row">
            <div class="col-md-6 justify-content-md-end">
                <h5>
                    The content of the Info
tab fsdsfssgdfsg sagfdd
fsgfdgdgd sgg sgdfgdgdd 
                </h5>
                <div class="float-right">
                    <button class="btn btn-primary m-1 ">Explore</button>
                    <button class="btn btn-primary m-1">Cantact</button>
                </div>
            </div>
            <div class="col-md-6 justify-content-md-start">
                <div id="logo1" class="float-left">
                    <img src="./../assets/logo.png" />
                </div>
                <div id="logo" class="float-left">
                <button @click="getResume" class="btn btn-primary">Get Resume</button>
                </div>
                
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:"Info",
    methods:{
        getResume: ()=>{
            console.log("Clicked Get Resume");
        }
    }
}
</script>   

<style >
    #logo{
        clear: left;
    }
</style>

