<template>
    <div class="container">
        <form >
            <div class="input">
                <h3 style="text-align: center">Sign up and get your quote today</h3>
                <div class="entry ">
                    <label style="padding-right:5px">Name</label>
                    <input type="text"  v-model="client.Name">
                </div>
                <div class="entry ">
                    <label style="padding-right:5px" >Email</label>
                    <input type="text"  v-model="client.Email">
                </div>
                <div class="entry">
                    <label style="padding-right:5px" >Phone</label>
                    <input type="text"  v-model="client.Phone">
                </div>
                <button style="width:50%" type="submit" @click.prevent="submitted" >Sign Up</button>
            </div>
        </form>
    </div>
</template>

<script>

export default {
    components: {
    },
    
    data() {
        return {
            client: {
                Name:'Joe Black',
                Email:'joe@blackmedia.com',
                Phone:'+44789456132'
            }
            
        }
    },
    methods: {
        submitted() {
            console.log(this.client)
        }
    }
}
</script>

<style scoped>
.input {
    /* width: 100%; */
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
    /* margin: 25px; */
     box-sizing: border-box;
    /* width: 280px; */
    padding: 8px;
    border: 1px solid rgb(0, 0, 0);
    box-shadow: 5px 5px 5px rgb(110, 107, 107);
    margin: 10px;
    background-color: white;
    border-radius: 25px;
}
.entry {
    /* width: 80%; */
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    align-content: center;
    margin: 10px;
}
</style>
