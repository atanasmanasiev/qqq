<template>
    <div class="content">
        <div class="top1">
            <div class="topContent">
                <h1>LOGO</h1>
            </div>
            <div class="topContent">
                <h3>Our customisable solutions suit any project no matter the size or platform</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus eget dignissim felis, in consectetur velit. Phasellus luctus, justo at posuere suscipit, metus diam accumsan purus, quis elementum lacus velit ac libero. Suspendisse egestas quam sed ante venenatis, nec sagittis nibh scelerisque</p>
            </div>
        </div>
        <div class="middle">
            <h1>Our Services</h1>
        </div>
        <div class="bottom">
            <div class="bottomContent">
                <p>Web Design / UI Design / Branding</p>
            </div>
            <div class="bottomContent">
                <p>Web/App Development</p>
            </div>
            <div class="bottomContent">
                <p>Scalable Cloud Hosting Solutions</p>
            </div>
        </div>
        <button>Details</button>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
/* .container { 
    width: 100%;
    height: 450px; 
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
    background-color: #bdb5a5af
} */
.content {
    /* height: 450px; */
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
    /* background-color: #bdb5a5af; */
    padding-bottom: 50px;
    
}
.top1 {
    /* width:40%; */
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
    margin: 10px;
}
.topContent {
    width:40%;
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
    margin: 10px;
}
.middle {
    width:100%; 
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 25px;
    padding: 25px

}
.bottom {
    width:100%; 
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
}
.bottomContent {
    width:25%;
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
    margin: 10px;
    padding: 10px;
    text-align: center
}
</style>
