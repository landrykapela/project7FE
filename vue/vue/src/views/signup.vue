<template>
    <div >
        <header>
 <img src="/photo/icon-left-font-monochrome-black.png" alt="groupomania" width="200px" height="200px">
 <aside class="sign"><a href="/signin.html"> Sign In </a></aside>
</header>



 <form class="container" id="myform"  method="post">
    <label for="uname">First Name</label>
    <input type="text" placeholder="Enter First Name" id="fname" name="fname" required/>

    <label for="uname">Surname</label>
    <input type="text" placeholder="Enter Surname" id="sname" name="sname" required/>

    <label for="email">E-mail</label>
    <input type="email" placeholder="Enter E-mail" id="email" name="email" required/>
    

    <label for="psw">Password</label>
    <input type="password" placeholder="Enter Password" id="psw" name="psw" required/>

    <input class="submit"   id="signupsubmit" value="SignUp" type="submit"/>
</form>
  
    </div>
</template>
<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
    setup() {
        
    },
})
</script>
