<template>
    <div class="content">
        <div class="top1">
            <div class="topContent1">
                <h1>Ease of use and transparicy</h1>
                <p>We operate open and transparent system where you are in control of your content and you don't have to wait in long lines to get a support</p>
            </div>
        </div>
        <div class="top2">
            <div class="top2Content"><h5>Easy manegement of your sites and content</h5></div>
            <div class="top2Content"><h5>Open contract on our hosting services <br>(Cancel anythime)</h5></div>
            <div class="top2Content"><h5>Security by default with SSL Certificates for Free</h5></div>
            <div class="top2Content"><h5>Technical support to answer any of your questions</h5></div>
        </div>
        <div class="middle">
            <div class="middleContent">
                <h2>Start your jorney with us today</h2>
                <button>Sign up</button>
            </div>
        </div>
            <div class="bottom">
                <div class="bottomLeft"><p>@2019 SourceTown LTD. SourceTown is registered trademark of Source Town Limited, company registered in Englang and Wales, 0000000</p></div>
                <div class="bottomLogo"><p>LOGO</p></div>
                <div class="bottomRight">
                    <ul style="list-style: none;">
                        <li><p>Company</p></li>
                        <li>About</li>
                        <li>Legal</li>
                        <li>Blog</li>
                    </ul>
                </div>
                <div class="bottomRight">
                    <ul style="list-style: none;">
                        <li><p>Services</p></li>
                        <li>Hosting</li>
                        <li>Emails</li>
                        <li>Development</li>
                    </ul>
                </div>
                <div class="bottomRight">
                    <ul style="list-style: none;">
                        <li><p>Support</p></li>
                        <li>Contact</li>
                        <li>Community</li>
                        <li>FAQ</li>
                    </ul>
                </div>
            </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.bottom {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 25px;
    padding: 25px
}
.bottomLeft {
    width: 30%
}
.bottomLogo {
    width: 30%
}
.bottomRight {
    width: 11%
}
.content {
    /* height: 450px; */
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
    background-color: rgb(25, 65, 59);
    padding-bottom: 50px;
    color: antiquewhite;
    text-align: center
    
}
.topContent1 {
    width:60%;
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
    margin: 10px;
}
.top1 {
    width:80%; 
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 25px;
    /* padding: 25px */

}
.top2 {
    /* width:100%;  */
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
}
.top2Content {
    width:20%;
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
    margin: 10px;
    padding: 10px
}
.middle {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    
    background-color: aqua
}
.middleContent {
margin: 25px;
    padding: 25px;
}
</style>
