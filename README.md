# Heroku Multi Procfile buildpack for java 

im deploying an app in heroku that was in a multi module java project
but heroku doesnt support multiple procfile to start a java app luckily i got
a buildpack that is a multi procfile buildpack 
https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-multi-procfile.
and combined to this buildpack 
https://github.com/heroku/heroku-buildpack-java

# steps on how to use this
- first put as many procfile as you want
- then define a config variable on your heroku app 
- make sure at resources tab you enable that one dyno that is generated by the buildpack
- deploy your app

