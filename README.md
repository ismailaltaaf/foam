# foam https://foam-f7d12.web.app
fieldset{
    height: 320px;
    width: 400px;
    
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="account.css">
    <title>Document</title>
</head>
<body>
    <fieldset id="01">
        <legend>Account</legend><br><br><br>
        E-mail Address <br> <input type="e-mail" value="@gmail.com"><br><br>
        Password <br> <input type="password" min="8"><br><br>
        Confirm Password <br> <input type="password"><br><br>
        <br>
        <a href="index.html"> <button>Back</button></a> 
        <a href="review.html"> <button>Next</button></a> 
    </fieldset>  
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>STEP 1:Personal Detail</h1>
    <h1>STEP  2:Account</h1>
    <h1>STEP 3:Your Review</h1>
    <form action="">
        <fieldset>
            <legend>Personal Details</legend>
        First Name <br> <input type="text" name="user name"><br><br>
        Last Name <br> <input type="text"><br><br>
        CNIC <br> <input type="number" name="CNIC"><br><br>
        Social Link <br> <input type="link" name="URL" value="https//" >
        <br><br>
        <button>
            <a href="account.html" target="-blank" >NEXT</a>
        </button>
          
        
    </form></fieldset>
    
</body>
</html>
fieldset{
        height: 400px;
        width: 380px;
    }
    
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="review.css">
    <title>REVIEW</title>
</head>
<body>
    <form action="">
    <fieldset>
        <legend>Your Review</legend><br>
        
        How did you hear about us?
        <select name="devices">
            <option value="newss">news</option>
            <option value="adds">adds</option>
            <option value="web">website</option>
            </select>
        
     <br><BR></BR>
        Would you visit again?<br>
        <input type="radio" name="select" > yes
        <input type="radio" name="select" > No
        <input type="radio" name="select" > May be 
        <br><br>
        Comments
        <br>
        <textarea name="comment"  cols="30" rows="5"></textarea>
        <br><br>
        Documents <br>
        <input type="file"><br><br>
        <input type="checkbox">Sign me up for update
        <a href="#"><button> Submit
        </button></a> 
       
        <br><br><br>
       <a href="account.html"><button>Back</button></a>  
        
    </form>
    </fieldset>
    
</body>
</html>
