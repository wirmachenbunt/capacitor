# capacitor

#create folder

mkdir myCapProject

#go to folder

cd myCapProject

#setup capacitor project

npm init @capacitor/app

cd my-app

npm i @capacitor/ios

npx cap add ios

npm run build

npx cap sync 

npx cap open ios

#copy cables files to public folder if cables CLI is installed

cables --export xOit4e -d /Users/chris/Desktop/capacitorTest/my-app/ios/App/App/public -c

edit index.html and add

allowLocalFileAccess:true,
