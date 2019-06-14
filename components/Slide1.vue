<template>
<div class="container">
    <Header />
    <div class="first_slide">
        <div class="left_txt">
            <div class="leftContent">
                <h1>We specialise in bulding and hosting of digitalproducts</h1>
                <p>Our platform allows you ti easily cretae and manage digital projects whether it is a small website or a large web aplication</p>
            </div>
        </div>
        <div class="rigth_sungUp" style=""><SignUp /></div>
    </div>
</div>   
</template>

<script>
import Header from './Header'
import SignUp from './SignUp'
export default {
    components: {
        SignUp,
        Header
    }
}
</script>

<style scoped>
.container {
background-color: rgb(10, 205, 175);
}
.first_slide { 
    /* width: 100%; */
    /* height: 450px; */
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
    
}
.leftContent {
    /* width:50%; */
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
    margin: 10px;
}
.rigth_sungUp {
    width: 50%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
    padding: 40px
}
.left_txt {
    width: 50%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
}
</style>
