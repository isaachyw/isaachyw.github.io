---
title: Contact Me
---

<style>
    /* Style for labels */
    label {
        display: block;
        font-weight: bold;
        margin-bottom: 0.2rem;
    }
    
    /* Style for inputs and select */
    input[type="email"],
    input[type="text"],
    select {
        display: block;
        width: 100%;
        padding: 0.5rem;
        font-size: 1rem;
        border: 1px solid #ccc;
        border-radius: 4px;
        margin-bottom: 1rem;
        box-sizing: border-box;
    }
    
    /* Style for file input */
    input[type="file"] {
        margin-bottom: 0.5rem;
    }
    
    /* Style for submit button */
    button[type="submit"] {
        background-color: #117bff;
        color: #fff;
        border: none;
        padding: 0.5rem 1rem;
        border-radius: 4px;
        font-size: 1rem;
        cursor: pointer;
    }
    
    /* Style for hr */
    hr {
        margin: 2rem 0;
        border: none;
        border-top: 1px solid #ccc;
    }
</style>

<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America%2FNew_York&src=aXNhYWNoeXdAdW1pY2guZWR1&src=Y19jN2UwYzNhYzA2ODZmNjE5MGUyMmNhNGFjOGFkN2VjZGU1Yzk0NDlhMTg0YmMxYTExNWJiMjc4MTc3MTA0MzFkQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=YWRkcmVzc2Jvb2sjY29udGFjdHNAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&src=ZW4uY2hpbmEjaG9saWRheUBncm91cC52LmNhbGVuZGFyLmdvb2dsZS5jb20&color=%23039BE5&color=%23795548&color=%2333B679&color=%230B8043" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>

<form accept-charset="UTF-8" action="https://getform.io/f/e05282ef-19eb-4a58-9798-7861b033b7f0" method="POST" enctype="multipart/form-data" target="_blank">
    <div class="form-group">
        <label for="exampleInputEmail1" required="required">Email address</label>
        <input type="email" name="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    </div>
    <div class="form-group">
        <label for="exampleInputName">Name</label>
        <input type="text" name="name" class="form-control" id="exampleInputName" placeholder="Enter your name" required="required">
    </div>
    <div class="form-group">
        <label for="exampleInputName">Comment</label>
        <input type="text" name="info" class="form-control" id="info" placeholder="Enter your comment" required="required">
    </div>
    <hr>
    <div class="form-group mt-3">
        <label class="mr-2">Upload your CV:(optional)</label>
        <input type="file" name="file">
    </div>
    <hr>
    <button type="submit" class="btn btn-primary">Submit</button>
</form>
