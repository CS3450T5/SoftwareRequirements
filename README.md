# Software Requirements

We recommend pursuing the development of an energy management system and dashboard due to the benefits gained in power efficiency and budget. This project will involve creating a dashboard to view and manage power distribution of the building. We believe that by limiting the scope to a dashboard for monitoring and a basic management system, an end-of-April integration deliverable can be achieved.

The functional requirements of this project involve:
| Priority | Feature                             | Description                                                                                      |
| -------- | ----------------------------------- | ------------------------------------------------------------------------------------------------ |
| 1        | Dashboard                           | A Place to display power distribution information (Analytics and stats                           |
| 2        | Real-Time power grid integration    | Database to keep track of real time data and offset from renewable energies                      |
| 3        | Predictive Load Balancing           | Directly managing energy usage in accordance to load and when the devices actually need energy   |
| 4        | Integration with renewable energies | Integrate renewable energy sources to better optimize energy usage with renewable energy in mind |

To build the minimum viable product (MVP), it will be necessary to develop the following key technologies:

| Feature                            | Dev Tasks                                                       |
| ---------------------------------- | --------------------------------------------------------------- |
| Dashboard for real-time monitoring | Webpage (ReactJS/TypeScript) and backend (Flask/Python)         |
| Basic load Balancing               | ML system trained on provided data                              |
| Connection to renewable energies   | Integrate data from renewable energy sources, show on dashboard |
