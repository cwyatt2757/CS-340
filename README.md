# CS-340

**Writing Maintainable, Readable, and Adaptable Programs**

Writing maintainable, readable, and adaptable programs begins with separating concerns and organizing code into logical, reusable components. In Project One, I created a CRUD Python module to handle database operations independently from the user interface logic. This modular approach made my Project Two dashboard significantly easier to build and maintain because all database interactions were abstracted into a single reusable class. Instead of rewriting connection logic or query handling, I simply imported the CRUD module and reused its methods.

The advantage of working this way was clear: if the database connection string, schema, or query logic needed to change, I only had to update the CRUD module rather than modify multiple parts of the dashboard. This improved maintainability and reduced redundancy. In the future, this CRUD module could be reused in other dashboard applications, web applications, APIs, or expanded into a RESTful service layer. It provides a scalable foundation for any project requiring MongoDB interaction.

**Approaching Problems as a Computer Scientist**

As a computer scientist, I approach problems by first understanding the requirements, then breaking them into smaller, manageable components. For the Grazioso Salvare dashboard, I analyzed the client’s needs—specifically filtering, visualization, and geolocation requirements—and translated them into technical tasks: database queries, data transformation, and UI rendering.

This project differed from previous assignments because it required integrating multiple layers: database management, backend logic, and front-end dashboard components. Rather than solving isolated coding problems, I had to think in terms of system design. I used an iterative approach—building the database connection first, validating queries, then layering visual components on top. In future projects, I would continue to use this layered development strategy, ensuring database integrity before building application logic. I would also incorporate more formal schema planning and indexing strategies to improve performance in larger datasets.

**What Computer Scientists Do and Why It Matters**

Computer scientists design systems that transform raw data into actionable insights. In this project, I built a dashboard that allows Grazioso Salvare to filter and visualize animal rescue data efficiently. Instead of manually reviewing large datasets, the organization can quickly identify patterns, geographic trends, and relevant records.

Projects like this matter because they improve decision-making. By building structured databases and interactive dashboards, computer scientists enable organizations to operate more strategically and efficiently. For a company like Grazioso Salvare, this type of system reduces time spent on data processing and increases time spent on mission-critical work, such as coordinating rescues and allocating resources effectively.
