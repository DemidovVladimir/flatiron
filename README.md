<br />
<p align="center">
  <a href="https://github.com/DemidovVladimir/flatiron">
    <img src="static/gophercises_logo.png" alt="Logo">
  </a>

  <h3 align="center">Flatiron task</h3>


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-task">People with cancer</a>
      <ul>
        <li><a href="#built-with">Build with</a></li>
      </ul>
    </li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE TASK -->
## About The Task

Create domains of people sick with the same type of the desiese and been treated with the same type of the drug.

Example of the incomming data:
* illnesses = ['person1, melonoma', 'person2, sarcoma', 'person3, sarcoma', 'person4, sarcoma']
* drugs = ['person1, drug1', 'person2, drug2', 'person3, drug3', 'person3, drug2', 'person4, drug3']
* domains = ['melonoma, drug1', 'drug2, drug3, sarcoma', 'sarcoma, drug3']

Examle of the output data:
* [['person1'], ['person2', 'person3', 'person4'], ['person4']]


### Built With

Python3 including standard libs: 
* itertools
* collections


<!-- GETTING STARTED -->
## Getting Started

To start using this project you have options:
* Open ipynb file directly in the repository and click command + enter buttons on the keyboard
* Start Jupiter Notebook in within python environment and open flatiron_task.ipynb

<!-- LICENSE -->
## License

No Licence available.


<!-- CONTACT -->
## Contact

Vladimir Demidov - [@linkedin](https://www.linkedin.com/in/vladimir-demidov-germany/) - uncojet@gmail.com
