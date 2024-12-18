# CS-340

How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?

For maintainability, the CRUD Python module from Project One separated database operations into reusable methods (create, read, update, delete). This separation allowed easy integration of MongoDB with the dashboard interface. For readability, I followed best practices such as consistent naming conventions, clear comments, and logical code structure. For example, variable names like 'filter_type' and functions such as 'update_dashboard()' made the purpose of the code easy to understand. For adaptability, the project was designed to allow future updates. For example, the 'update_dashboard' callback can filter additional rescue types without modifying the core logic. The use of Dash components also made it easy to add new interactivity features like dropdowns and charts. The CRUD Python module can be reused in future projects to manage other types of data within a MongoDB database. It provides a flexible and efficient way to query and update information.

How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?

When approaching this project, I broke down the request from Grazioso Salvare into functional tasks. These tasks included connecting to MongoDB, retrieving and filtering animal data, and displaying it visually. I used the Dash framework for the dashboard and MongoDB for the database. I prioritized functionality such as data filtering, pie charts, and geolocation mapping. I worked step-by-step, starting with the CRUD operations and then building the dashboard's features. Testing at each step made sure that everything worked correctly as I went along. Debugging errors I received in the callbacks and refining features like dropdowns improved the final application. 

What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?

Computer scientists solve real-world problems using computational tools and techniques. For this specific project, the dashboard enables Grazioso Salvare to efficiently filter and analyze rescue animal data. This can improve decision-making and streamline their operations. For example, the data filtering was addressed with a dropdown menu that allows users to focus on specific rescue types. I created visualizations of the data with a pie chart and a geolocation map that provide insights into animal breeds and locations, which are important for resource allocation. Using MongoDB and Python allowed me to automate data retrieval and display. This type of work helps organizations make data-driven decisions, save time, and improve outcomes, demonstrating the value of computer science in supporting businesses.
