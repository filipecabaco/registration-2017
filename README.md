# Worker Registration

Simple application that uses Holiday XLS to create the Worker Registration Excel Sheet

## How to use

### Generate Jar

1. `brew install leiningen`
1. Run `chmod 755 registration.jar`
1. `lein uberjar`

### How to run

`java -jar registration.jar Feb 2017 "Filipe Cabaço" ~/Desktop/2018.xlsx ~/Desktop/Filipe\ Cabaço.png 2017-Feb-FilipeCabaco.xlsx`

## Arguments

1. `vacation` - the vacation XLSX file
1. `signature` - PNG picture of your signature
1. `month` - Month for the registration sheet you want
1. `year` - Year for the registration sheet you want
1. `name` - Employee name
1. `filename` - Filename for the saved XLSX file
