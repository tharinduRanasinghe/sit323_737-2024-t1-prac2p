<h1 style="font-size:28px; font "><b>Instructions</b></h1>
<p><b>Step 1:</b> Clone the project</p>
<p><b>Step 2:</b> In the terminal, type <b><i>npm install</i></b>. This command installs the packages listed in the package.json file.</p>
<p><b>Step 3:</b> After installing the packages, type <b><i>node start</i></b>. This command runs the server, allowing you to access the application on port 3040 via localhost.</p>
<h2>Important files and their purposes are as follows</h2>
<p><b>Index.html- </b>It consists of a form with two input fields labeled "Number 1" and "Number 2," where users can input numerical values.
             Upon submission, the form sends an asynchronous request to an Express.js server endpoint /addTwoNumber, passing the entered numbers as query parameters. 
             The server processes the numbers, adds them together, and returns the result, which is then displayed below the form.</p>
 
<p><b>server_get.js- </b> This Express.js application serves a HTML file located in the "html" directory. 
                It provides an API endpoint /addTwoNumber, which accepts two numbers as query parameters and responds with the sum of those numbers in JSON format. 
                The server listens on port 3040, and upon running, it logs a message indicating that it's listening on the specified port.</p>
 

<p><b>Package.json- </b> The package.json file describes the Node.js project named "sit323_737-2024-t1-prac2p". 
               It includes metadata such as the project name, version, and description. 
               The main script for the project is "server.js". Additionally, it specifies a start script to run the server using node server_get.js. 
               It also mentions that the project is hosted on GitHub and uses the MIT license. Express.js version 4.18.3 is listed as a dependency in the package.json.</p>
