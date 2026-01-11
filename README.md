<h1 align="center">Welcome to my Docker assignment for ASL!</h1>


---

### Technologies 

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?logo=node.js&logoColor=white)

---

### Description

This project focuses on creating and using individual Docker containers in different programming languages to print out a string, which in this case would be "Hello ASL!" We were also required to display the current date along with the greeting. I chose Python and NodeJS as my languages of choice for this assignment. 

---

### How to run 

1. Clone this repo and open it in your preferred code editor of choice.
2. Open the terminal.
3. For Python, cd into the "python_example" folder.
4. Build the image by putting in the command "docker build -t python-asl ." and hitting enter.
5. Then run the container by putting in the command "docker run --rm python-asl"
6. You should see "Hello ASL!" returned in the terminal with the current date!

7. For NodeJS it's much of the same, cd into the "nodejs_example" folder via the terminal.
8. Build the image by typing in "docker build -t node-asl ." and hitting enter.
9. Then run the container bby typing in "docker run --rm node-asl"
10. just like before, you should see "Hello ASL!" returned in the terminal followed by the cuurent date!

