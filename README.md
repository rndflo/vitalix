# Vitalix

## Vitalix is the react-native app that consumes that API that is exposed by satoshi which is a fork of rndflo.io

## Codemy



//------------------------------------------------------------------------------------------------------------------------------------
## Steps
==> rails new vitalix --api -d mysql -T --no-rdoc --no-ri

//------------------------------------------------------------------------------------------------------------------------------------
==> rails generate model Project title:string desc:string

//------------------------------------------------------------------------------------------------------------------------------------


## In the top-level vitalix folder
==> create-react-app vitalix

//------------------------------------------------------------------------------------------------------------------------------------

==> rails g controller Projects

//------------------------------------------------------------------------------------------------------------------------------------

==> rails s -p 3001



curl -G http://localhost:3001/api/v1/projects

//------------------------------------------------------------------------------------------------------------------------------------

==> npm install webpack -g

==> cd vitalix && npm install webpack --save-dev


//------------------------------------------------------------------------------------------------------------------------------------