# Vehicle Management System

The Vehicle Management System is a web application developed using ASP.NET Core MVC, integrating SignalR for real-time communication. This system allows users to control and monitor the movement of multiple vehicles, including cars and trucks, through an intuitive web interface.

## Key Features

- **Vehicle Management:**
  - Add, edit, and remove Vehicle Makes and Models.
  - Add and edit Cars and Trucks with specific details.

- **Real-Time Updates:**
  - Utilizes SignalR for real-time communication between the server and clients.
  - Enables immediate updates on the user interface as vehicles change their status.

- **Vehicle Control Center:**
  - Centralized interface to manage the current list of vehicles.
  - Options to control vehicles by selecting between "Drive," "Stop," and "Reverse" modes.
  - Displays real-time information such as kilometers driven and status.

- **Optional Features:**
  - View a list of historical trips.
  - Override the average speed of a vehicle.
  - Disable and delete vehicles as needed.

## Technologies Used

- **ASP.NET Core MVC:** Framework for building web applications using the Model-View-Controller pattern.
- **SignalR:** Library for adding real-time functionality to web applications.
- **Entity Framework Core:** Object-relational mapping (ORM) for database interactions.
- **HTML, CSS, and JavaScript:** Front-end technologies for creating a dynamic and responsive user interface.

## How to Run

1. Clone the repository from GitHub.
2. Open the project in Visual Studio.
3. Configure the database connection in the `appsettings.json` file.
4. Run migrations to create the necessary database tables.
5. Start the application and navigate to the home page.

## Note

This is a basic implementation, and additional features or optimizations can be added based on specific requirements. Users can interact with the system through the web interface, and real-time updates provide a seamless and responsive experience for managing a fleet of vehicles.

Feel free to customize the description based on the specific functionalities and goals of your Vehicle Management System.
