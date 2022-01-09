# Project Title

This project entailed creating an application that finds qualifying loans for customers. It takes in information from the client, such as monthly debt, home value, and desired loan amount. It then calculates DTI, LTV, and then filters the loans accordingly. Using csv writer, it saves the qualifying loans to a csv file for the client. 

---

## Technologies

The project is written using python 3.9.2. As far as imports, it uses the Path library, fire module, questionary module and the csv module. 

---

## Installation Guide

fire and questionary require pip installs, which is easily done through the following code:

  pip install fire

  pip install questionary

Be sure to check the python version in your environment, as it needs to match 3.9.2. 


---

## Usage

<img width="542" alt="Screen Shot 2022-01-09 at 3 39 00 PM" src="https://user-images.githubusercontent.com/95647683/148699910-962cf89c-55d5-47ea-bec7-28eefae8c950.png">

This section is where we import the needed libraries and modules. Further, we import the filter functions from qualifier, located in the utils library. 

<img width="614" alt="Screen Shot 2022-01-09 at 3 40 25 PM" src="https://user-images.githubusercontent.com/95647683/148699970-600ed595-b488-4e89-9ad9-41b6c1a17280.png">

This section defines the function through which the user defines the path to the csv file of bank data, which the program will use to calculate the aforementioned statistics. 


<img width="730" alt="Screen Shot 2022-01-09 at 3 41 46 PM" src="https://user-images.githubusercontent.com/95647683/148699997-f5797a8d-936e-4078-a75b-3dfaf4753814.png">

This section is where we defined the function that gathers the clients bank data. Three of the variables are float, and one is integer. Thus, an input of float for credit score will lead to the cessation of the program. 

img width="767" alt="Screen Shot 2022-01-09 at 3 44 17 PM" src="https://user-images.githubusercontent.com/95647683/148700073-2b6f204d-e5f9-4c9b-a663-1ac0c7f17dfb.png">

<img width="717" alt="Screen Shot 2022-01-09 at 3 44 23 PM" src="https://user-images.githubusercontent.com/95647683/148700079-88f8c846-ff5c-4180-a461-256f8d4a9565.png">

This section is where the program calculates the desired statistics, and then matches them to loans in the csv path input from the client. 

img width="627" alt="Screen Shot 2022-01-09 at 3 45 41 PM" src="https://user-images.githubusercontent.com/95647683/148700152-aed93a5d-5c4f-485b-81b5-9f7d6da81a23.png">

This is where the user is prompted with a confirm.ask() as to whether they would like to save their qualifying loans to a csv. If yes, they are prompted to enter a path for their desired output csv. 


---

## Contributors

In this section, list all the people who contribute to this project. You might want recruiters or potential collaborators to reach you, so include your contact email and, optionally, your LinkedIn or Twitter profile.

The contributors to this project include yours truly, John Doyle, and the developers of the GWU FINTECH Bootcamp. My email is jpdoyle1999@gwu.edu for inquiries. 

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
