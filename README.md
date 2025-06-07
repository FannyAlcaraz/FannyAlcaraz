body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background-color: #3e1f47;
  color: #ffffff;
}

header {
  background-color: #5e2b73;
  padding: 20px;
  text-align: center;
}

h1 {
  color: #d9a0f7;
}

nav ul.menu {
  list-style: none;
  padding: 0;
  margin: 0;
  background-color: #4b2c5f;
  display: flex;
  justify-content: center;
}

nav ul.menu > li {
  position: relative;
  margin: 0 15px;
}

nav ul.menu > li > a {
  display: block;
  padding: 10px 15px;
  color: white;
  text-decoration: none;
}

.submenu {
  display: none;
  position: absolute;
  background-color: #6e3a85;
  list-style: none;
  padding: 0;
  margin: 0;
  top: 100%;
  left: 0;
  min-width: 150px;
}

.submenu li a {
  padding: 10px;
  display: block;
  color: white;
}

nav ul.menu li:hover .submenu {
  display: block;
}

main {
  padding: 20px;
}

section {
  background-color: #5a2a6d;
  margin-bottom: 20px;
  padding: 15px;
  border-radius: 10px;
}

footer {
  text-align: center;
  padding: 10px;
  background-color: #4b2c5f;
  color: #ccc;
}
