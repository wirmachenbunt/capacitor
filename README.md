i'm using brew on osx terminal to install things
https://brew.sh/index_de

and via brew i installed node.js
brew install node

and you need xcode with ios installed


# capacitor

#create folder

mkdir myCapProject

#go to folder

cd myCapProject

#setup capacitor project

npm init @capacitor/app

cd my-app

npm i @capacitor/ios

brew install cocoapods #install cocoapods

npx cap add ios

npm run build

npx cap sync 

npx cap open ios

#copy cables files to public folder if cables CLI is installed

cables --export xOit4e -d /Users/chris/Desktop/capacitorTest/my-app/ios/App/App/public -c

edit index.html and add

allowLocalFileAccess:true,

<img width="759" alt="image" src="https://user-images.githubusercontent.com/1138673/200085757-8f2b1fe9-4331-4f9a-aa97-bcd75a2c0d53.png">

