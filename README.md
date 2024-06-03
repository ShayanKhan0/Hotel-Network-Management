# Modern Hotel Network Project

As a part of our end-year networking project, we designed and implemented a modern hotel network. The hotel comprises three floors, each hosting different departments. The first floor accommodates the Reception, Store, and Logistics departments. The second floor houses the Finance, HR, and Sales Marketing departments. The third floor is dedicated to the IT and Admin departments. Below are the key considerations taken into account during the design and implementation:

1. Three routers connecting each floor (all placed in the server room in the IT department).
2. All routers are interconnected using serial DCE cables.
3. The network between the routers follows these subnets: 10.10.10.0/30, 10.10.10.4/30, 10.10.10.8/30.
4. Each floor has one switch (placed in the respective floor).
5. Each floor has WIFI networks connected to laptops and phones.
6. Each department has its own printer.
7. Each department is assigned to a different VLAN with the following details:

   - *1st Floor:*
     - Reception - VLAN 80, Network: 192.168.8.0/24
     - Store - VLAN 70, Network: 192.168.7.0/24
     - Logistics - VLAN 60, Network: 192.168.6.0/24

   - *2nd Floor:*
     - Finance - VLAN 50, Network: 192.168.5.0/24
     - HR - VLAN 40, Network: 192.168.4.0/24
     - Sales - VLAN 30, Network: 192.168.3.0/24

   - *3rd Floor:*
     - Admin - VLAN 20, Network: 192.168.2.0/24
     - IT - VLAN 10, Network: 192.168.1.0/24

This network design ensures efficient communication between departments while maintaining security and segmentation.

## Project Structure

- project-files/: Contains all the network configuration files and diagrams.
- report/: Detailed project report including network design, configurations, and analysis.
- presentation/: Presentation and video demonstration of the project.

## Contribution

Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

## Credits

Special thanks to Mobeen Shoukat for his contributions and support.
