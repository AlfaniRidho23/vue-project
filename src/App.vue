<script setup>

</script>

<template>
  <h1><center>Pangeran Barbershop </center></h1>
  <center><img src="logo_barbersoap-removebg-preview (3).png" alt="logo.png" style="width:322px;height:330px;" /> </center>
  <center><h2>Login costumer Barbershop </h2></center>
  <center><form action="/action_page.php">
        <label for="usname">Username:</label>
        <input type="text" id="usname" name="usname"><br><br>
        <label for="password">Password:</label>
        <input type="text" id="Password" name="Password"><br><br>
        <input type="submit" value="Submit">
    </form></center>
 
  <h3>Usia dan harga</h3>
  <table >
        <tr>
            <th>usia </th>
            <th> harga</th>
            <th>usia </th>
            <th> harga</th>
            <th>usia </th>
            <th> harga</th>
        </tr>
          <tr>
            <td>Anak-Anak</td>
            <td>10k</td>
            <td>Remaja</td>
            <td>18k</td>
            <td>Dewasa</td>
            <td>25k</td>
          </tr>
 

    </table>
  <h4>Komentar</h4>
  <form action="/action_page.php">
    <p><label for="barbershoap">Review :</label></p>
    <textarea id="w3review" name="w3review" rows="4" cols="50">Kritik Dan Saran</textarea>
    <br>
    <a href="https://www.w3schools.com/html/html_links.asp">KLIK DISINI</a>
  </form>

</template>

<style scoped>
table, th, td {
  border:2px solid rgb(18, 19, 19);}

</style>
<style>
form {margin-top: 1%;}
 body { background-image: url ("pw.jpg");
 background-size: cover;}
 table, th, td {border:2px solid black;}
</style>

