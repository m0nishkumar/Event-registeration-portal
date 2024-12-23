
# BIT Hackathon Registration Website  

A dynamic and user-friendly website designed for the **BIT Hackathon**, allowing participants to register their teams, sign up for events, and stay updated with the latest announcements and schedules.

## Features  

### User Registration  
- Individual user accounts with secure login functionality.  

### Team Registration  
- Seamless team creation and management.  
- Team leaders can add or remove members and register the team for specific events.  

### Event Registration  
- Participants can view all available events and register for them.  
- Events categorized by type (e.g., coding, design, innovation).  

### Real-time Updates  
- Dedicated section for announcements, ensuring participants never miss important updates.  
- Countdown timer to the hackathon start date for increased engagement.  

### Dashboard  
- A personalized dashboard for each participant/team to view:  
  - Registered events.  
  - Team details.  
  - Hackathon schedule.  

### Admin Panel  
- Admin access for managing events, viewing registrations, and broadcasting announcements.  

### Responsive Design  
- Fully optimized for desktops, tablets, and mobile devices.  

## Tech Stack  
- **Frontend**: HTML, CSS, JavaScript (for interactive elements).  
- **Backend**: PHP for server-side functionality and business logic.  
- **Database**: MySQL for storing user, team, and event data.  
- **Hosting**: Deployed on a web server with PHP and MySQL support.  

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/bit-hackathon.git  
   cd bit-hackathon  
   ```  

2. Set up the database:  
   - Create a MySQL database and import the `database.sql` file provided in the project folder.  
     ```sql  
     CREATE DATABASE hackathon;  
     USE hackathon;  
     SOURCE database.sql;  
     ```  

3. Update database credentials:  
   - In the `config.php` file, update the following lines with your database details:  
     ```php  
     define('DB_SERVER', 'localhost');  
     define('DB_USERNAME', 'your_username');  
     define('DB_PASSWORD', 'your_password');  
     define('DB_DATABASE', 'hackathon');  
     ```  

4. Run the application:  
   - Deploy the project files to your web server with PHP support.  
   - Ensure that the MySQL server is running and accessible.  

5. Open the application in your browser:  
   - Navigate to `http://localhost/bit-hackathon` or your server's address.  

## Roadmap  
- [ ] Add email notifications for team registration confirmation.  
- [ ] Integrate a payment gateway for paid events.  
- [ ] Add analytics for event registrations.  

## Contributing  
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.  
