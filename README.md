# html_stuff
Html prototype

λοιπον το index εχει μεσα καποια πραγματα:
  εχει ενα div που ειναι κατι σαν ενα κουτι μεσα στον χωρο της οθονης
  μεσα σε αυτο εχει ενα λινκ που περιεχει το logo, αν πατησεις στο λογκο θα δεις πως σε παει στο index.html γιατι αυτο εβαλα
  στο href επεισης εβαλα και μια κλαση λογκο για να μπορω να ελεγχω το στυλ, την θεση του μεσα στο  div και αλλα.
  μετα απο κατω μπορεις να δεις οτι υπαρχει μια λιστα.
  το home σε παει στο index.html(αναδρομη)
  το About ομως σε παει σε ενα αλλο html αρχειο οπου ειναι το ιδιο ακριβως απλος μετα στο αλλο div που εχει σαν κλαση
  w_container εχω γραψει αλλες μαλακιες οποτε οταν πατας στο about σε παει σε εκεινες τις μαλακιες
  το 3ο δεν το εχω κανει, σκεφτομαι να πεταγετε ενα κουτακι με τις πληροφοριες
  
το σταιλς εχει τα χροματα και ολες τις διαφορες μλκιες που αλλαζουν το στυλ μεσα στη σελιδα

υ.γ. το λογκο το εκανα επειδη βαριομουν στη ζωγραφικη αν δεν σου αρεσει καμεις καλυτερο
    μπορεις να βαλεις οτι φωτογραφια θες βαλε κανα τοπιο αν ειναι για background η οτι θες
    (μην βαλεις γυμνες και μας μπαναρουν)


σκεφτικα οτι μπορει να θες και το παλιο οποτε παρτο:

<!DOCTYPE html>
<html>
  <head>
    <style>
      html, body {
/*         transform: center; */
        height: 100%;
        width: 100%;
        margin: 0;
        padding: 0;
        background: linear-gradient(to bottom, #3399ff 0%, #8599ad 100%);
      }
      ul{
        list-style-type: none;
        margin: 0;
        padding: 0;
/*         overflow: hidden; */
/*         background-color: #333333; */
/*         #color:	#ffffff; */
      }
      
      h1{
        padding: 0;
        text-align:center;
/*         #background: linear-gradient(to bottom, #8599ad 0%, #b3bfcc 100%); */
      }
    </style>
  </head>
  <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p><br>

    <h2> Coooler than ice </h2><br>
    <ul>
      <li> water </li>
      <li> chocolate </li>
      <li> milk </li>
      <li> corn flakes </li>
    </ul>

  </body>
</html>
