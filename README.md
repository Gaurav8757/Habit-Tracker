<h1>Habit Tracker Pro</h1>
<hr>
<h3> How to run the Website ?</h3>
### Version: 2.0.0

### Usage

```sh
$ npm install
```

```sh
$ npm start
# Or run with Nodemon
$ npm run dev

# Visit http://localhost:8000
```

### MongoDB

Open "config/" and add your MongoDB URI, local or Atlas
<p>Either clone the repository and run or use above Link</p>
 open cmd with folder :----------------
 nodemon start index.js------------------
 open browser : --------------------
 localhost:8000
<hr>
<h3> How to Add  your  own mongodb ?</h3>
Go on -> config folder ->  
mongoose.connect('mongodb+srv://<username>:<password>@cluster0.8jpev.mongodb.net/<dbname>?retryWrites=true&w=majority')
<h2> Brief Intro about the Website</h2>
<p>
LoopBit is a habit tracker website made using <b>NodeJS</b>, <b>MongoDB</b> and vanilla <b>JavaScript.</b><br> Here you can keep a record of your day to day habits.You can create a habit and check you record for past few days.<br>
We can also remove a habit which we don't need anymore.
</p>
<hr>
<h2> Flow of Website : <h2>
<h4>
Home Page
</h4>
<p>
The home page is very basic and simple you have a  navbar on top with a search bar to filter out habits two button<br>
1.Add a habit and this will be shown in list on same page<br>
2.Show my streak button to show your progress from past 7 days
</p>
<h4>
Details Page
</h4>
<p>
Here You can see all your habits and you can change the status of all the habits as done,not done or pending.
Here also you can use search bar to filter out your habits according to requirement.
</p>


</p>
