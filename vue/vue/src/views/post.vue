<template>
    <div>
        <header>
 <img src="/photo/icon-left-font-monochrome-black.png" alt="groupomania" width="200px" height="200px">

</header>

<div class="menu"> 
  <a href="/home.html"><i class="fas fa-home"></i></a>
  <a href="/account.html"><i class="fas fa-user"></i></a>
  <a href="/signin.html"><i class="fas fa-sign-out-alt"></i></a>

</div>

<form class="post">

     <label for="text"> Title </label>
    <input type="text" id="title" placeholder="Title" name="title" required/>

    <label for="message">Description</label>
    <textarea rows="10" id="message"> Share your thoughts </textarea> 

    <label for="date-created">Date</label>
    <input type="date" placeholder="Date" id="date-created" name="Date" required/>
    <label for="image">Image</label>
    <input type="file" placeholder="Enter image" id="image" name="img" required class="image" accept="image/*,video/mp4" />
<br>
  <input class="submit"  id="postSubmit" type="submit"/>
</form>
    </div>
</template>