# react-native-todo
root
-----
username
password

npm install -g @aws-amplify/cli


project:
---------
url: https://www.instamobile.io/mobile-development/react-native-aws-amplify/

expo init react-native-todo

Create a New AWS IAM User
-----------------------------
amplify configure
username : amplify-isaac
ID de clé d'accès :
Clé d'accès secrète:
mot de passe : 

Integrating AWS Amplify in React Native
-----------------------------------------
code . from cmd
amplify init

dep : npm i aws-amplify aws-amplify-react-native

// after other import statements
import Amplify from 'aws-amplify';
import config from './aws-exports';
Amplify.configure(config);

Authentication
---------------
amplify add auth

amplify push

github repo
------------

echo "# react-native-todo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/slimeVidas26/react-native-todo.git
git push -u origin master

npm install

# react-native-todo-1
