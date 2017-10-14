# Twitter Oauth login with java play framework
Twitter login authentication to a java play 2.6.x web application.
<p>
This is an integration of Twitter login to a web application implemented in java play framework 2.6.x version .
</p>

<p>
<b>Which required and optional stories have you completed?</b>

- You can create a login page with a login button to web app.
- After clicking login button, you will be asked for his twitter credentials.
- After entering twitter account credentials, you will be logged in and redirected to home page of the web app. 

</p>

<p>
<b>Details of Twitter Oauth login implementation:</b>
  <p>

- First created an application on twitter which is needed to authorise user using twitter to our implemented web app. You can create twitter app at:
  href="https://apps.twitter.com/app/new"
- When your twitter app is created you can see his created app in My apps: href="https://apps.twitter.com/"
- Then entering into your twitter application, you can see "keys and access token" link, where lies your "CONSUMER KEY" and "CONSUMER   SECRET".
- Then, I have created a "Twitter" class under Controllers package : app/controllers/Twitter.java
- You have to enter your Twitter application's consumer key and secret into Twitter controller class.
- Added twitter routes in my routes file: conf/routes
- Added dependency "ws" in buid.sbt file: /build.sbt
- You can refer this documentation here: href="https://www.playframework.com/documentation/2.6.x/JavaOAuth#OAuth"

</p>

GIF demo of Twitter authentication (using LiceCap)
Added
</p>

<p>
Demo Link: <a href=https://github.com/nishchal31/Twitter-Oauth-login-with-java-play-/blob/master/Demo/Twitter%20login%20when%20not%20already%20logged%20in.gif"> <br> <br>
<img border="0" alt="W3Schools" src="https://github.com/nishchal31/Twitter-Oauth-login-with-java-play-/blob/master/Demo/Twitter%20login%20when%20not%20already%20logged%20in.gif" width="100%" height="100%"> <br>
</a>
</p>
