<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Saya M.Badri,Full Stack Developer Dari Indonesia Riau</h2>
    <hr/>
    <p><i>I have experience in web site,App Mob design & building and customization.</i></p>
    <p><i>Also I am good at html, css, javascript, php, jquery, bootstrap, Laravel, Java, Mysql.</i></p> 
    <p><i>I love to talk with you about our unique approach.</i></p> 
    <p><i>free to contact me writing an email with your project idea.</i></p>
    <h3>Skill</h3>
    <table>
    <tr>
        <th>Technologies</th>
        <td>Python</td>
        <td>Java</td>
        <td>Larafel framework</td>
    </tr>
    <tr>
        <th>Soft Skills</th>
        <td>Problem Solving</td>
        <td>Team Work</td>
        <td>Flexibilty</td>
    </tr>
</table>
    <h3>Contacts</h3>
    <ul>
      <li><a href="https://github.com/muhammadbadri250901" target="_blank" rel="noopener">Github</a></li>
      <li><a href="https://www.freecodecamp.org/" target="_blank" rel="noopener">Freecodecamp</a></li>
      <li><a href="https://www.instagram.com/" target="_blank" rel="noopener">Instagram</a></li>
    </ul>
    <h2>Write me a message</h2>
<form>
    <input placeholder="Name" required /><br>
    <input placeholder="Email" required /><br>
    <textarea placeholder="Message" required ></textarea><br>
    <input type="submit" value="SEND"/>
</form>
<!-- Footer Section -->
<footer>
      <p>&copy; 2024 M. Badri. All Rights Reserved.</p>
      <p>
        Follow me on:
        <a href="https://github.com/muhammadbadri250901" target="_blank">Github</a> |
        <a href="https://www.instagram.com/" target="_blank">Instagram</a>
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
table {
  border: 2px solid #42b983;
  border-radius: 3px;
  display: inline-block;
  background-color: #fff;
}

th {
  background-color: #42b983;
  color: rgba(255, 255, 255, 0.66);
  cursor: pointer;
  user-select: none;
}

td {
  background-color: #f9f9f9;
}

th,
td {
  min-width: 120px;
  padding: 10px 20px;
}

th.active {
  color: #fff;
}

th.active .arrow {
  opacity: 1;
}

 form{
  display: inline-block;
}

footer {
  margin-top: 50px;
  padding: 20px;
  background-color: #f9f9f9;
  color: #2c3e50;
  text-align: center;
  border-top: 1px solid #ddd;
}

footer a {
  color: #42b983;
  text-decoration: none;
  font-weight: bold;
}

footer a:hover {
  text-decoration: underline;
}

</style>
