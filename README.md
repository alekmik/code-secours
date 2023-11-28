# code-secours
codes utiles


<h1>HTML</h1>

<h2>Formulaire : </h2>

<form  action="#"  method="post">
    <div>
      <label  for="nom">Nom :</label>
      <input  type="text"  id="nom"  name="user_name">
    </div>
    <div>
      <label  for="courriel">Courriel :</label>
      <input  type="email"  id="courriel"  name="user_email">
    </div>
    <div>
      <label  for="message">Message :</label>
      <textarea  id="message"  name="user_message"></textarea>
    </div>
    <div>
        <label  for="subject">Sujet :</label>
        <select name="user_subject" id="subject">
            <option value="">--Please choose an option--</option>
            <option value="dog">Dog</option>
            <option value="cat">Cat</option>
            <option value="hamster">Hamster</option>
            <option value="parrot">Parrot</option>
            <option value="spider">Spider</option>
            <option value="goldfish">Goldfish</option>
        </select>
    </div>
    <div  class="button">
      <button  type="submit">Envoyer votre message</button>
    </div>
</form>

Récupérer les données via la "method" :
- $_GET
- $_POST
Par ex :
  <?php
    echo  $_GET['user_name'];
  ?>
