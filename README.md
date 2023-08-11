# SymphonicNomad-Band-Moniker-Maven

This is a simple web application that generates random band names by combining adjectives and nouns. Users can trigger the generation of a new band name by submitting a form.


## BAND NAME GENERATOR

The Band Name Generator web application is built using Node.js and the Express.js framework. It uses EJS templates to dynamically display band names on the user interface. The generator combines randomly selected adjectives and nouns to create unique band names.

The application includes the following files:

- footer.ejs: Defines the footer section of the HTML template, including the copyright information.
- header.ejs: Contains the header section of the HTML template, including meta tags and a link to an external CSS file.
- index.ejs: The main content of the web page. It displays the generated band name or a welcome message and includes a form to generate a new name.
- index.js: The main server file. It sets up the Express server, handles routes, and generates and displays random band names.
- public/: A directory containing static files, such as styles and scripts.
- styles/main.css: The main stylesheet for the application.
- README.md: This file, providing information about the project.


## INSTALLATION

1. Clone the repository to your local machine using Git:
```bash
git clone https://github.com/your-username/SymphonicNomad-Band-Moniker-Maven.git
```

2. Navigate to the project directory:
```bash
cd SymphonicNomad-Band-Moniker-Maven
```

3. Install the required dependencies using npm:
```bash
npm install
```

```bash
npm install express
```

```bash
npm install ejs
```

```bash
npm install body-parser
```


## USAGE

1. Run the application by executing the following command:
```bash
nodemon index.js
```

2. Open your web browser and navigate to http://localhost:3000 to access the Band Name Generator.
   
3. Click the "Generate Name" button to generate a new band name.


## DEPENDENCIES

- Express.js
- EJS (Embedded JavaScript)
- body-parser


## CONTRIBUTING

Contributions to the Band Name Generator are welcome! Feel free to fork this repository, create a new branch, and submit your pull requests.


## LICENSE

This project is licensed under the MIT License.


