<template>
    <div class="hello " style="background: wheat">
        <h2>Register</h2>
        <form @submit="checkForm">
            <form-group label="Mobile Number">
                <input v-model="mNumber" type="number" placeholder="Mobile Number">
            </form-group>
            <br>
            <form-group label="First Name">
                <input v-model="fName" type="text" placeholder="First Name">
            </form-group>
            <br>
            <form-group label="Last Name">
                <input v-model="lName" type="text" placeholder="Last Name">
            </form-group>
            <br>
            <form-group label="DOB" align="center">
                <date-dropdown default="1970-01-01" v-model="selectedDate"></date-dropdown>
            </form-group>
            <br>
            <form-group label="Sex">
                <input type="radio" id="male" value="male" v-model="checkedSex">
                <label for="male">Male</label>
                <input type="radio" id="female" value="female" v-model="checkedSex">
                <label for="female">Female</label>
            </form-group>
            <br>
            <form-group label="Email">
                <input v-model="rMail" type="email" placeholder="Email Address">
            </form-group>
            <br>
            <form-group>
                <button class="" type="submit">Register</button>
            </form-group>
            <br>
        </form>
    </div>
</template>
<script>
    export default {
        name: "C_Login"
    }
</script>

<style scoped>
    h3 {
        margin: 40px 0 0;
    }
    ul {
        list-style-type: none;
        padding: 0;
    }
    li {
        display: inline-block;
        margin: 0 10px;
    }
    a {
        color: #42b983;
    }
    .hello {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        margin: 32px 0;
    }

</style>
