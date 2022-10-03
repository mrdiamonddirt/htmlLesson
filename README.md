<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RowDog Developer Page</title>
</head>
<body>
    <div>
    <h1 style="text-align: center; color: rgba(0, 0, 243, 0.554); font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;">About Me<br/>RowDog<br/>The Aspiring Full Stack Developer</h1>
    <img id="profileimg" src="image/profile.png" alt="my profile pic">
</div>
    <div id="secondDiv">
    <h2 style="text-align: center; color: white;">Favorite Foods</h2>
        <ul>
            <li style="font-family: 'Courier New', Courier, monospace;">Pizza</li>
            <img height="40" src="https://freesvg.org/storage/img/thumb/Pizza-Slice-in-Tango-Colors.png" alt=""><p>Delicious <sub>pizza</sub> With <sup>Meat ON</sup></p>
            <li>Pie</li>
            <img height="40" src="https://freesvg.org/storage/img/thumb/Slice-Cherry-Pie-S.png" alt="">
            <li>Burgers</li>
            <img height="40" src="https://freesvg.org/storage/img/thumb/food-sammich.png" alt="">
        </ul>
        <div id="thirdDiv">
        <h3 style="text-align: center; color:blueviolet">Favorite Movies</h3>
            <ol>
                <li>Enemy of the state</li>
                <a href="https://www.imdb.com/title/tt0120660/" target="_blank">
                <img height="100" src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcQw-tfev51yV7zx0ObgZiOcogqOZ2HUV6FUrKnWcPHWtirYp34x" alt="">
                </a>
                <li>Law abiding citizen</li>
                <a href="https://www.imdb.com/title/tt1197624/">
                <img height="100" src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcR4dyw44sRqOsGxRci8oaHShDS0NnXDaRtGD1K2xZ9k9l36nWs6" alt="">
                </a>
            </ol>
        </div>
        <p>
            a List of <q>Skills</q> I wish to acquire <br> why i am interested in developing my Skills Developing my skills as a <q>Web Developer</q> and why
        </p>
        <ol>
            <li name="listitem1"> what skills i want to develop
                <ul>
                    <li>My planning skills</li>
                    <li>My team working skills</li>
                    <li>My code writing skills</li>
                </ul>
            </li>
            <li name="listitem2">
                Why i want to develop these skills
                <ol>
                    <li>Potentially further my career</li>
                    <li>Because i like to learn</li>
                    <li>i will become a better teacher</li>
                    <ul>
                        <li>to help my kids to develop there computer skills from an early age</li>
                    </ul>
                </ol>
            </li>
        </ol>
    </div>
    <audio autoplay loop>
        <source src="sounds/AMBForst_Forest (ID 0100)_BSB.ogg" type="audio/mpeg">
    </audio>
    <div id="wilhelmScream">
    <legend for="scream">Wilhelm Scream</legend>
    <audio id="scream" autoplay preload="auto" controls
        <source src="sounds/Wilhelm scream.ogg" type="audio/ogg">
      Your browser does not support the audio element.
      </audio>
        <iframe alt="you browser does't support iframes" width="338" height="602" src="https://www.youtube.com/embed/95mTGGfwZug" title="Onupdate(scream) screaming whelm everytime I type in visual studio" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <h5 style="color: blue;">Start Of The Form</h5>
    <!-- Form which will send a GET request to the current URL -->
<form method="get">
    <label>Name:
      <input name="submitted-name" autocomplete="name">
    </label>
    <button>Save</button>
  </form>
  
  <!-- Form which will send a POST request to the current URL -->
  <!-- <form method="post">
    <label>Name:
      <input name="submitted-name" autocomplete="name">
    </label>
    <button>Save</button>
  </form> -->
  
  <!-- Form with fieldset, legend, and label -->
  <form method="post">
    <fieldset>
      <legend>Form Inputs</legend>
      <label><input type="radio" name="radio"> Select me</label>
      <label><input type="radio" name="radio"> Select me</label>
      <label><input type="checkbox" name="checkbox"> Tick Me</label>
      <label><input type="checkbox" name="checkbox"> Tick Me</label>
    </fieldset>
  </form>
    <br>
    <button id="scream" onclick="document.getElementById('scream').play();">Press this button to scream</button>
    <br>
    <textarea id="textTest" name="textTest" rows="5" cols="100">this text is in a text area you could but anything you want in here but everytime i update this file in visual studio code it wilhelm Screams at me and yeah i coded it and i could turn it off but after 100's of screams i still find it funny 😊</textarea>
    <div>
    <iframe src="https://www.copsrp.com" height="auto" width="auto"></iframe>
    </div>
</body>
<br>
<footer style="background-color: white; margin: auto; border: 1px solid black; border-radius: 5px;">
    <a href="https://github.com/mrdiamonddirt" target="_blank" alt="github website">Link to my Github</a>
    <a href="https://copsrp.com" target="_blank" alt="CopsRP website">CopsRP website</a>
</footer>
<style>
    #wilhelmScream {
        border: 1px solid rgba(59, 57, 57, 0.356);
        border-radius: 5px;
    }
    #scream {
        display: block;
        margin: auto;
    }
#secondDiv {
    display: block;
    margin: auto;
    border: 1px solid rgba(59, 57, 57, 0.356);
    border-radius: 5px;
    background-color: rgb(31, 223, 111);
}
#thirdDiv {
    display: block;
    margin: auto;
    border: 1px solid rgba(59, 57, 57, 0.356);
    border-radius: 5px;
    background-color: rgba(43, 43, 43, 0.727);
    color: white;
}
iframe {
    border-radius: 5px;
    border: 2px solid rgb(20, 39, 211);
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
    height: 500px;

}
    footer {
        text-align: center;
    }
    h1 {
        border: 5px;
        border-color: black;
    }
body {
    background-color: rgb(21, 229, 215);
    }
footer {
    background-color: aqua;
}
#profileimg {
    display: block;
    margin-left: auto;
    margin-right: auto;
    border-radius: 13px;
    width: 20%;
    object-fit: cover;
}
</style>
</html>