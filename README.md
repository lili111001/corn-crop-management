# 👨‍🌾 Corn Crop Management App 🌽
This is a full stack web app, as the tittle says, a crop management app, for now it's focused on corn but functionalities to manage other types of crops can be added (scalable).

<h2>Functionalities</h2>
A user can:

- Create, log in and manage their acount.
- Register basic information about their crops (crop name, sowing date, sowing site, plot size, number of plants per square meter).
- Add relevant events, for example whether there was any plague or disease that affected any crops, or a brief description on the growth of the plants.
- Check weather forecasts that may be important for the development of their crops, like any drowghts or heavy rains. <b><i>(This of course has its limitations since the version of the api used is free).</i></b>
- Schedule tasks (i.e. crop spraying, fertilization, irrigation)
- Get monthly reports about their crops, these reports consist of:
  - Basic crop info (crop name, sowing date, sowing site, plot size, number of plants per square meter).
  - Relevant events: A list of registered events (i.e pests, diseases, growth, etc), a description and date of each event.

    <b>For example:</b>

    - 15/03/2024: Worm infestation detected on Plot 1.
    - 25/03/2024: First signs of growth observed.
    - 10/04/2024: Mild fungal disease detected and treated.
    
  - Scheduled Tasks: A list of the mentioned tasks, with a description, date and scheduled future tasks

    <b>For example:</b>

    - 05/03/2024: Initial spraying carried out.
    - 20/03/2024: First irrigation carried out.
    - 30/04/2024: Fertilization programmed.
  - Weather conditions: Relevant weather forecasts
  - Performance analisis: Comparison with previous crops or historical averages
<h2>Technologies</h2>

- <b>Back: Springboot:</b> <i>since spring framework provides architecture scalability, for now this app is a monolith, but depending on the demand of resources, it could evolve into a microservices architecture.</i> 
- <b>Front: Vuejs </b>
- <b>Database: PostgreSQL</b>

<h2>System Diagrams</h2>

Following the c4 model, the next diagrams are usefull to understand how the system works

- <b>System Context Diagram:</b>

![System Context Diagram](https://github.com/user-attachments/assets/fcf9d48a-31bf-4715-af19-5bc2d3f83fcf)


- 


