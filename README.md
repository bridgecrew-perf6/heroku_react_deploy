# heroku_react_deploy

# Config 
"engine" : {
    "node": "xxxxxxx",
    "npm" : "xxxxxx"
}

# Start Script
"start" : "react-scripts start -p $PORT",

# Add Script
"heroku-postbuild" : "npm run build"
