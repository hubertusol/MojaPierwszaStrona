<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Moja pierwsza strona</title>
</head>

<body>
  <div id="head">
   <h1>Hubert Sołtys</h1>
    <img src="https://choosingchia.com/jessh-jessh/uploads/2016/08/watermelonpizza3-1-of-1-1.jpg" alt="msdbkddsds">
  </div>
  <hr/>
  <div id="About">
    <h2>O mnie</h2>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur tempor sapien in urna blandit ullamcorper. Quisque mollis ipsum non condimentum pretium. Ut sagittis nunc eu enim porta, eu eleifend nibh tincidunt. Integer at efficitur nisi. Nullam ornare sem mauris, et pulvinar eros euismod vel.
  </div>
  
  <hr/>
  <div id="s">
   <h2>Ankieta</h2>
      <form>
        <input type="text" name="name" list="nick" placeholder="Twój nick"><br>
          <datalist id="nick">
              <option value="xyz" />
              <option value="abc" />
              <option value="efg" />
          </datalist>
        <input type="radio"name="gender"value="male">
        <label for="male">Mężczyzna</label><br>
        <input type="radio" name="gender" value="female">
        <label for="female">Kobieta</label><br>
        <h4>Jakie owoce lubisz?</h4>
        <input type="checkbox" name="fruit" value="apple"> 
        <label for="apple">Jabłko</label><br>
        <input type="checkbox" name="fruit" value="cherry"> 
        <label for="cherry">Wiśnia</label><br>
        <input type="checkbox" name="fruit" value="peach"> 
        <label for="peach">Brzoskwinia</label><br>
        <input type="checkbox" name="fruit" value="mango"> 
        <label for="mango">Mango</label><br>
        <button type="submit">Wyślij</button>
      </form>
    </div>
  <hr>
  <div id="vegetables" class="fav">
      <h2>Moje ulubione warzywa</h2>
       <ol>
         <li>Marchew</li>
         <li>Pomidor</li>
         <li>Sałata</li>
         <li>Papryka
           <ul>
             <li>Czerwona</li>
             <li>Żółta</li>
             <li>Zielona</li>
           </ul>
         </li>
         <li>Ogórek</li>
      </ol>
    </div>
    <hr>
    <div id="contact">
       <a href="https://www.facebook.com" target=blank>Facebook</a>
       <a href="https://www.instagram.com" target=self>Instagram</a>
       <a href="https://www.snapchat.com" target=blank>Snapchat</a>
    </div>
</body>

</html>
