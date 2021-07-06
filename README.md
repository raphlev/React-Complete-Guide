# Course Javascript Udemy

React - The Complete Guide 2021 (Beginner + Advanced)

https://www.udemy.com/course/react-the-complete-guide-incl-redux
https://github.com/academind/react-complete-guide-code


# React-CompleteGuide-Udemy.pdf

https://drive.google.com/file/d/1zWrHlb8cpaG7jJIOcN4s5NAYMt0vI0Qu/view?usp=sharing

# configure firebase

console.firebase.google.com

Create Firebase RealTime database using Test Mode

https://console.firebase.google.com/project/practice-food-order-http-forms/database/practice-food-order-http-forms-default-rtdb/data

Replace all original URLs with new one:
https://practice-food-order-http-forms-default-rtdb.europe-west1.firebasedatabase.app

List All files with 'firebase' inside js file which are stored in src subfolders only (exluding any other subfolders and files - including subfolders below src folder)
find . -type f -wholename "**/src/*.js" -exec grep -l 'firebase' {} \;

List All Content with 'firebase' inside js file which are stored in src subfolders only (exluding any other subfolders and files - including subfolders below src folder)
find . -type f -wholename "**/src/*.js" -exec grep 'firebase' {} \;

Replace domaine name (URL) 'react-http-6b4a6.firebaseio.com' into 'practice-food-order-http-forms-default-rtdb.europe-west1.firebasedatabase.app' inside js file which are stored in src subfolders only (exluding any other subfolders and files - including subfolders below src folder)
find . -type f -wholename "**/src/*.js" -exec sed -i 's/react-http-6b4a6\.firebaseio\.com/practice-food-order-http-forms-default-rtdb\.europe-west1\.firebasedatabase\.app/g' \{\} \;  -print

## create meals object for 17-practice-food-order-http-forms
Required to test 17-practice-food-order-http-forms project

Add manually meals document using database real time url access:
https://console.firebase.google.com/project/practice-food-order-http-forms/database/practice-food-order-http-forms-default-rtdb/data

It can match this example taken from starting project:

practice-food-order-http-forms-default-rtdb > +
meals > value +
 m1 > value +
    name: 'Sushi'
    description: 'Finest fish and veggies'
    price: 22.99
 m2 > value +
    name: 'Schnitzel'
    description: 'A german specialty!'
    price: 16.5
 m3 > value +
    name: 'Barbecue Burger'
    description: 'American, raw, meaty'
    price: 12.99
 m4 > value +
    name: 'Green Bowl'
    description: 'Healthy...and green...'
    price: 18.99

# start any project folder

Example: cd ~/VSCode/React-Complete-Guide/15-building-custom-react-hooks/07-using-the-hook-in-more-cmp
npm i && npm start
