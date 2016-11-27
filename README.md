# angular2_web-Firebase-Starter
This Project can be a starter for a Angular2 Project with Firebase connection already made. You just have to alter your FirebaseKeys to proceed.
# Quick Start
Make sure you have Node version >= 5.0 and NPM >= 3

	Clone/Download the repo then edit app.ts inside /src/app/app.ts

**clone our repo** `git clone https://github.com/GSThina/angular2_web-Firebase-Starter.git`

**change directory to our repo**: `cd angular2_web-Firebase-Starter`

**install the repo with npm**: `npm install`

**start the server**: `npm start`

go to **http://0.0.0.0:3000** or **http://localhost:3000** in your *browser*

You can start coding from now on!

# Firebase Connection
You can get your Firebase App Config from firebase console of your Firebase App. You just have to paste that details in the `src/app/home/home.ts`
    
	  // Initialize Firebase
	  var config = {
	    apiKey: "",
	    authDomain: "",
	    databaseURL: "",
	    storageBucket: "",
	    messagingSenderId: ""
	  };
	  firebase.initializeApp(config);
	  
Once you are done editing this, you can now use Firebase Documentation to work on with your Firebase DB.

In case you want to initialize firebase globally, you can give the above snippet in the `index.html` inside your <script></script> tag.
