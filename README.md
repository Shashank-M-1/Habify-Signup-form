# Habify Signup form
 Sign-up form
 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Signup page</title>
</head>
<style>
    body{
        font-family: 'Work Sans', sans-serif;
        font-size: 15px;
    }
    p{
        color:rgb(178,175,170);
    }
    .signin button{
        margin-left: 1440px;
    }
    .logo img{
        height: 90px;
        width: 200px;
        margin-left: 620px;
        margin-top: 80px;
    }
    fieldset{
        margin-left: 400px;
        margin-top: 40px;
    }
    .logo h3{
        margin-left: 520px;
    }
    .logo p{
        margin-left: 520px;
    }
    hr{
        width: 41.5%;
        margin-left: 400px;
    }
    table{
        border-spacing: 10px;
        width: 10%;  
    }
    td button{
        background-color:green;
    }
    .first-name{
        display: flex;
    }
    .first-name input{
        margin-left: 10px;
    }
    .user-name{
        display: flex;
    }
    .user-name input{
        margin-left: 16px;
    }
    .email{
        display: flex;
    }
    .email input{
        margin-left: 42px;
    }
    .pass{
        display: flex;
    }
    .pass input{
        margin-left: 19px;
    }
    .pass button{
        background: rgb(16,228,58);
        background: radial-gradient(circle, rgba(16,228,58,1) 100%, rgba(0,212,255,1) 100%);
    }
    .privacy label{
        border: 1px solid grey;
        padding: 4px;
    }
    .auto label{
        border: 1px solid grey;
        padding: 4px;
    }
    .link img{
        border-radius:50%;
        height: 50px;
        width: 50px;
        margin-left: 40px;
    }
    .text label{
        margin-left: 50px;
    }
    .categories label{
        border: 1px solid grey;
        padding: 4px;
    }
    .terms label{
        padding-right: 70px;
    }
    .btn button{
        margin-left: 20px;
        height: 50px;
        width: 90%;
        color: azure;
        background-color: red;
    }
</style>
<body>
    <p align="right">Already have an account?</p>
    <div class="signin">
        <button>Sign In</button>
    </div>
   <div class="logo">
    <img src="D:\HABIFY\Assignment - Front-End Developer - Habify\EFA_Registered Logo.png" alt="" style="border-bottom: 1px solid grey;">
    <h3>Create an Emotional First Aid - Enabler Account</h3>
    <p align="justify">By singin up you can start posting,replaying to topics,earn badges,<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;favorite,vote topics and many more.</p><hr>
   </div>
   <form action="">
    <fieldset style="width: 40%;">
        <div class="first-name">
            <label for="First Name">First Name:</label>
            <input type="text" name="" id="First Name" placeholder="Jane" required>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <label for="Last Name">Last Name:</label>
            <input type="text" name="" id="Last Name" placeholder="Doe" required>
        </div><br>
        <div class="user-name">
            <label for="Username:">Username: </label> 
            <input type="Username" name="" id="Username:" placeholder="Janeuntiy9" required>
        </div><br>
        <div class="email">
            <label for="Email:">Email:</label>
            <input type="email" name="" id="" placeholder="Jane326@gmail.com" required>
        </div><br>
        <div class="pass">
            <label for="Password:">Password:</label> 
            <input type="password" name="" id="Password:" placeholder="****************************" required>&nbsp;&nbsp;<button>Strong</button>
        </div>
        <div class="privacy">
            <h4>Privacy Settings(OPTIONAL)</h4>
            <p>Who can see my profile?</p>
                <input type="checkbox" name="" id="Everyone"><label for="Everyone">Everyone</label>
                <input type="checkbox" name="" id="Only friends"><label for="Only friends">Only friends</label>
                <input type="checkbox" name="" id="Invite Only"><label for="Invite Only">Invite Only</label>
        </div>
        <div class="auto">
            <p>Automatically share my posts and replies on Social Networks</p>
                <input type="checkbox" name="" id="Facebook"><label for="Facebook">Facebook</label>
                <input type="checkbox" name="" id="Twitter"><label for="Twitter">Twitter</label>
                <input type="checkbox" name="" id="Google+"><label for="Google+">Google+</label> 
        </div>
        <div class="survey">
            <p>How old are you?</p>
            <select name="" id="">
                <option value="">21</option>
            </select>
            <p> Who are you?</p>
            <select name="" id="">
                <option value="">Female</option>
            </select>
            <p> Will you be friendly here?</p>
            <select name="" id="">
                <option value="">Select</option>
            </select>
            <p> Where did you here about us?</p>
            <select name="" id="">
                <option value="">Search Engine</option>
            </select>
        </div>
        <div class="link">
            <h4>Link Social Networks(OPTIONAL)</h4>
            <img src="Facebook-logo.png" alt="">
            <img src="twitter-logo.jpg" alt="">
            <img src="google+logo.png" alt="">
            <img src="ytlogo.png" alt="">
            <div class="text">
                <label>Facebook&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Twitter&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Google+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Youtube</label>
            </div>
        </div>
        <div class="categories">
            <h4>Intrested Categories(OPTIONAL)</h4>
            <h4>Categories I'm interested in</h4>
            <input type="checkbox" name="" id="Select All"><label for="Select All">Select All</label>
            <input type="checkbox" name="" id="Mental Health"><label for="Mental Health">Mental Health</label>
            <input type="checkbox" name="" id="MH Tips"><label for="MH Tips">MH Tips</label>
            <input type="checkbox" name="" id="Support"><label for="Support">Support</label><br><br>
            <input type="checkbox" name="" id="Enabler"><label for="Enabler">Enabler</label>
            <input type="checkbox" name="" id="Exchange"><label for="Exchange">Exchange</label>
            <input type="checkbox" name="" id="Art"><label for="Art">Art</label>
            <input type="checkbox" name="" id="Q&As"><label for="Q&As">Q&As</label>
            <input type="checkbox" name="" id="Social"><label for="Social">Social</label><br><br>
            <input type="checkbox" name="" id="Random"><label for="Random">Random</label>
            <input type="checkbox" name="" id="Pets"><label for="Pets">Pets</label>
            <input type="checkbox" name="" id="Music"><label for="Music">Music</label>
            <input type="checkbox" name="" id="Science"><label for="Science">Science</label>
            <input type="checkbox" name="" id="Education"><label for="Education">Education</label>
            <input type="checkbox" name="" id="Video"><label for="Video">Video</label>
        </div><br>
        <div class="terms">
            <input type="checkbox" name="" id="AgreeT&C" required><label for="AgreeT&C">I Agree to the terms and conditions</label>
            <input type="checkbox" name="" id="Sub" required><label for="Sub">Subscribe to the newsletter</label>
        </div><br>
        <div class="btn">
            <button>Create new Account</button>
        </div>
    </table>
    </fieldset>
</form>
</body>
</html>
