# facebook project
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=\\, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="images/logo.png">
   <title>Facebook - Login in or sign Up</title>
  </head>
  <body>

    <div id="container"\>
      <div id="recent-logins">
        <img id="facebook" src="https://static.xx.fbcdn.net/rsrc.php/y8/r/dF5SId3UHWd.svg" alt="facebook-logo">
        <div id="title">recent-logins</div>
          <div id="subtitle">click your picture or add an account</div>
          <div id="cards">
            <div id="card-1">
              <div id="cancel">x</div>
              <img id="card-1-img" src="images/profile.jpg" alt="profile picture">
              <div class="username">VARDHAN REDDY</div>
            </div>
            <div id="card-2">
              <img id="card-2-img" src="images/add.webp" alt="add account">
              <div id="add-account" class="username">Add Account</div>
            </div>
          </div>
      </div>
      <div id="login">
        <input type="email" placeholder="Email or Phone Number">
        <input type="password" placeholder="Password">
        <input type="button" value="Log In" id="login-button">
        <a href="#">Forgor Password?</a>
        <hr style="width:95%;">
        <input type="button" value="Create New Account" id="Create-new-account">
        <p><strong>Create a Page</strong>Create a Page for a celebrity,brand or business.</p>
       </div>
    </div>
   <footer>
    <div>
      English (UK)
      मराठी
      हिन्दी  
      اردو 
     ગુજરાતી
     ಕನ್ನಡ
     ਪੰਜਾਬੀ
     தமிழ்
     বাংলা
     తెలుగు
     മലയാളം
     <hr style="width:100;">
     Sign UpLog InMessengerFacebook LiteWatchPlacesGamesMarketplaceFacebook PayOculusPortal
     InstagramBulletinLocal
    <br>
    FundraisersServicesVoting Information CentreGroupsAboutCreate adCreate PageDevelopersCareers
    PrivacyCookiesAdChoicesTermsHelpContact uploading and non-usersSettingsActivity log
    <br><br>
     Meta © 2022
    </div>
   </footer>
  </body>
</html>
CSS Code:)
body {
    text-align: center;
    width: 100%;
    margin: 0 auto;
    padding: 0px;
    font-family: "lucida grande",tahoma,verdana,arial,sans-serif;
    background: linear-gradient(white, #D3D8E8);
}

#header_wrapper {
    width: 100%;
    min-width: 980px;
    background-color: #4c66a4;
}

#header {
    width: 980px;
    margin: 0px auto;
    padding: 0px;
    height: 85px;
}

    #header li {
        list-style-type: none;
        float: left;
        text-align: left;
        color: white;
    }

    #header #sitename {
        margin-top: 25px;
    }

        #header #sitename a {
            color: white;
            text-decoration: none;
            font-size: 30px;
            font-weight: 900;
        }

    #header form {
        margin-top: 15px;
        float: right;
    }

        #header form li {
            font-size: 13px;
            margin-left: 15px;
        }

            #header form li a {
                color: #A9BCF5;
                text-decoration: none;
            }

        #header form input[type="text"] {
            margin-top: 3px;
            margin-bottom: 3px;
            width: 150px;
            border: 1px solid #08298A;
            height: 25px;
            padding-left: 3px;
        }

        #header form input[type="password"] {
            margin-top: 3px;
            margin-bottom: 3px;
            width: 150px;
            border: 1px solid #08298A;
            height: 25px;
            padding-left: 3px;
        }

        #header form input[type="submit"] {
            height: 25px;
            margin-top: 20px;
            background-color: #084B8A;
            color: white;
            border: 1px solid #08298A;
        }

#wrapper {
    margin: 0 auto;
    padding: 0px;
    text-align: center;
    width: 980px;
}

    #wrapper div {
        float: left;
        font-family: helvetica, arial, sans-serif;
    }

    #wrapper #div1 {
        margin-top: 30px;
        width: 590px;
        text-align: left;
    }

        #wrapper #div1 p {
            font-size: 20px;
            font-family: arial;
            font-weight: bold;
            margin: 0px;
            color: #0e385f;
        }

    #wrapper #div2 {
        margin-top: 10px;
        width: 390px;
        text-align: left;
    }

        #wrapper #div2 h1 {
            margin: 0px;
            font-size: 37px;
            color: #2E2E2E;
        }

        #wrapper #div2 p {
            font-size: 18px;
            color: #2E2E2E;
        }

        #wrapper #div2 li {
            list-style-type: none;
            margin-top: 10px;
        }

            #wrapper #div2 li #firstname {
                width: 49%;
            }

            #wrapper #div2 li #surname {
                margin-left: 2%;
                width: 49%;
            }

            #wrapper #div2 li input[type="text"] {
                width: 100%;
                height: 40px;
                border-radius: 5px;
                padding-left: 10px;
                font-size: 18px;
                border: 1px solid #BDBDBD;
            }

            #wrapper #div2 li input[type="password"] {
                width: 100%;
                height: 40px;
                border-radius: 5px;
                padding-left: 10px;
                font-size: 18px;
                border: 1px solid #BDBDBD;
            }

            #wrapper #div2 li select {
                padding: 4px;
                float: left;
            }

            #wrapper #div2 li a {
                margin-left: 10px;
                width: 150px;
                color: #045FB4;
                text-decoration: none;
                font-size: 11px;
                display: inline-block;
                vertical-align: middle;
                line-height: 15px;
            }

                #wrapper #div2 li a:hover {
                    text-decoration: underline;
                }

        #wrapper #div2 li {
            color: #2E2E2E;
            font-size: 18px;
        }

        #wrapper #div2 #terms {
            color: #424242;
            font-size: 11px;
        }

            #wrapper #div2 #terms a {
                display: inline;
                margin: 0px;
            }

        #wrapper #div2 li input[type="submit"] {
            width: 205px;
            height: 45px;
            text-align: center;
            font-size: 19px;
            margin-top: 10px;
            margin-bottom: 10px;
            font-family: 'Freight Sans Bold', helvetica, arial, sans-serif !important;
            font-weight: bold !important;
            background: linear-gradient(#67ae55, #578843);
            background-color: #69a74e;
            box-shadow: inset 0 1px 1px #a4e388;
            border-color: #3b6e22 #3b6e22 #2c5115;
            border: 1px solid;
            border-radius: 5px;
            color: #fff;
            cursor: pointer;
            display: inline-block;
            position: relative;
            text-shadow: 0 1px 2px rgba(0,0,0,.5);
        }

        #wrapper #div2 #create_page {
            color: #424242;
            font-size: 13px;
            font-weight: bold;
        }

            #wrapper #div2 #create_page a {
                display: inline;
                margin: 0px;
                font-size: 13px;
            }

#footer_wrapper {
    width: 100%;
    clear: both;
    float: left;
    margin-top: 30px;
    min-width: 995px;
    background-color: white;
    text-align: left;
}

#footer1 {
    width: 980px;
    margin: 0px auto;
    padding: 0px;
    border-bottom: 1px solid #E6E6E6;
    height: 30px;
    line-height: 30px;
    font-size: 12px;
    color: #848484;
}

    #footer1 a {
        color: #365899;
        display: inline;
        margin-left: 10px;
        text-decoration: none;
    }

        #footer1 a:hover {
            text-decoration: underline;
        }

#footer2 {
    width: 980px;
    margin: 0px auto;
    padding: 0px;
    font-size: 12px;
    color: #848484;
}

    #footer2 a {
        color: #365899;
        display: inline-block;
        margin: 5px;
        margin-left: 0px;
        min-width: 80px;
        text-decoration: none;
    }

        #footer2 a:hover {
            text-decoration: underline;
        }
