<Grovery.html>
<html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grocery List</title>
    <link rel="stylesheet" href="style.css" />
 </head>
    <main>
    <h3>Can Grocery Chains Please Stop Price Gouging?</h3>
    </main>
 <body>
    <section>
        <div class="Pantry"> 
            <header>
                <h2>Pantry Items</h2>
            </header>
            <img src="https://imgs.search.brave.com/3F32Iykn-K7SC4RmrSDyjaJg4mycTWUVZg6SfZ1Z4jE/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTYw/Njc4NjQyL3Bob3Rv/L3BhbnRyeS1kZXRh/aWwuanBnP3M9NjEy/eDYxMiZ3PTAmaz0y/MCZjPU0tQWEySHc3/bllpMnVMQ0tXQXo1/RGVuWjZ5cHUxWHpX/S19BOVRvczU4NG89">
            <ul>
                <li>Noodles</li>
                <li>Rice</li>
                <li>Cereal</li>
                <li>Sweets</li>
            </ul>
        </div>
    </section>
    <section>
        <header>
            <h3>Fridge and Freezer</h3>
        </header>
        <img src="https://imgs.search.brave.com/D4crcDeXmCy9nCdY3246vasjUHEW3vZ5NGosgYGtI1Y/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly90My5m/dGNkbi5uZXQvanBn/LzA2LzQ2LzY5LzM2/LzM2MF9GXzY0NjY5/MzY4Nl8xWHoxTlJX/bHBJYXNnSGZ2Qmlt/Q0NGNW9sa3ZPUHYz/RS5qcGc">
        <div class="Fridge and Freezer">
            <header>
                <h1>Fridge</h1>
            </header>
            <ul>
                <li>Almond Milk</li>
                <li>Eggs</li>
                <li>Cheese</li>
                <li>Combucha</li>
            </ul>
            <header>
                <h2>Freezer</h2>
            </header>
            <ul>
                <li>Turkey Burgers</li>
                <li>Frozen Waffles</li>
                <li>Ice Cream</li>
            </ul>
        </div>
    </section>

    <table class="table">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">Cleaners</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>Soap</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td>Fabuloso</td>
          </tr>
          <tr>
            <th scope="row">3</th>
            <td colspan="2">Mop Heads</td>
          </tr>
          <tr>
            <th scope="row">4</th>
            <td colspan="2">Lysol Wipes</td>
          </tr>
        </tbody>
      </table>
    
</body>
</html>


style.css
section {
  display: inline-block;
  background-color: rgb(149, 189, 146);
  width: 320px;
  height: 900px;
  padding: 10px;
  border: 5px solid gray;
  margin: 50;
}
header {
  display: inline-block;
  background-color: rgb(142, 142, 204);
  width: 150px;
  height: 50px;
  border: 15px solid rgb(0, 0, 0);
  padding: 20px;
  margin: 20px;
}
title {
  background-color: rgb(236, 163, 163);
}
img {
  width: 200px;
  margin: 20px;
  padding: 20px;
  border: 5px solid rgb(243, 7, 7);
}
.element {
}
body {
  background-color: rgb(255, 255, 255);
}
table {
  background-color: rgb(185, 235, 136);
}

thead {
  background-color: rgb(135, 135, 189);
}
div {
}
main {
    display: table-caption;
    background-color: rgb(218, 50, 50);
    width: 400px;
    border: 15px solid rgb(0, 0, 0);
    padding: 20px;
    margin: 20px;
  }

h3 {
    display: inline-block;

  }
h2 {
    display: inline-block;
    height: 500px;
}
h1 {
    display: inline-block;
    height: 200px
}
