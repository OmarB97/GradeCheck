# T-Grade

Warning: this is still in alpha stage!

T-Grade is an application which does all the "hard work" for you so you don't have to worry about constantly checking your gradebook on T-Square all the time. Just took an exam? No worries, T-Grade's got your back! It'll send you a notification when that grade has been entered in. It's as simple as that!

At this point in time, you must already have node and npm installed on your computer beforehand to run this. Additionally, this will only work on Linux-based platforms, with plans to support Windows in the future!

So, the first step will be to clone the repository using the following command (or manually by using the green "clone" button on github):

    git clone https://github.com/OmarB97/T-Grade.git

Next, to obtain all required dependencies, simply run:

    npm install
    
If you are running this for the first time, you will be prompted for your login credentials, so you will need to manually run the application (only the first time) using:

    node main.js

Afterwards, to allow the application to periodically run and notify you whenever a grade is posted, simply run:

    node setup.js


If you come across any issues or would like to make a contribution, please submit an issue or a pull request! Thank you, and enjoy!
