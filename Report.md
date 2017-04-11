**Assignment 3 : NAGIOS**
=======
**System Practicum**
-------
### Group 13
- Kumari Shubhangi - B13122
- Harsh Gupta - B14109
- S.Priyadharshinee - B14117 
- Umang Agarwal - B14137
- Naman Agarwal - B14324
---

### Time Slots of Data Collection
- Thursday - 8:00 pm to 2:00 am
- Saturday -  8:00 pm to 2:00 am
- Monday -  8:00 pm to 2:00 am

---

#### General Observation
- CPU Load and RAM Usage of Server is directly proportional to the number of Users on a particular day.
- On a working day the average number of users of academic services like insite and webopac is higher in comparison to a holiday.

---
#### Server Specific Observations
##### students.iitmandi.ac.in
- On an average working day the user load is less between 8 am to 11 am - 12 pm, this might be because students are in the class and hence there is less traffic on server.
- CPU Load matches with the data of User load and is directly proportional to User Load.
- Ping times increases during the time there are more users on network, indicating that students connect to the student server to check their emails or browse internet when they are not in their classes.
- Comparing user load of different days, number of users connecting is as high as 400 at around 2 pm on Thursday, while it is as low as 40 around the same time on Sunday indicating that Sunday being a holiday the time i.e. 2 pm is a prime time to have lunch and hence the low traffic.

##### insite.iitmandi.ac.in
- User load on each day is almost similar except for Sunday for which it is a bit less, indicating that people often check insite services.
- CPU load following the same trend as that of User Load.
- Ping time doesn't follow any particular trend.

##### network.iitmandi.ac.in
- User load on network is low as compared to insite or student servers
- The RAM Usage on network server is almost constant throughout the time and doesn't change on any day at any time.
- On thursday at around 11:00 am, when there is a peak in ping time of all services of iitmandi, the ping of network service goes critical to 5,000 ms indicating some sort of network failure as there are no huge differences visible in user load at that time.
- CPU load follow the same trend as that of User Load.

##### webopac.iitmandi.ac.in
- Ping did not seem to follow any trend and there is insufficient data to correlate other factors.
- Data of CPU usage, RAM usage and User load could not be recieved.

---

#### Graphs
##### Thursday : (8:00 am to 2:00 pm)

- students.iitmandi.ac.in  

![cpu Students](https://github.com/saif-ali/nagios/blob/master/thursday_cpu_students.png?raw=true)
![ram Students](https://github.com/saif-ali/nagios/blob/master/thursday_ram_students.png?raw=true)
![ping Students](https://github.com/saif-ali/nagios/blob/master/thursday_ping_students.png?raw=true)
![user Students](https://github.com/saif-ali/nagios/blob/master/thursday_user_students.png?raw=true)  

- insite.iitmandi.ac.in  

![cpu insite](https://github.com/saif-ali/nagios/blob/master/thursday_cpu_insite.png?raw=true)
![ram insite](https://github.com/saif-ali/nagios/blob/master/thursday_ram_insite.png?raw=true)
![ping insite](https://github.com/saif-ali/nagios/blob/master/thursday_ping_insite.png?raw=true)
![user insite](https://github.com/saif-ali/nagios/blob/master/thursday_user_insite.png?raw=true)  

- network.iitmandi.ac.in  

![cpu network](https://github.com/saif-ali/nagios/blob/master/thursday_cpu_network.png?raw=true)
![ram network](https://github.com/saif-ali/nagios/blob/master/thursday_ram_network.png?raw=true)
![ping network](https://github.com/saif-ali/nagios/blob/master/thursday_ping_network.png?raw=true)
![user network](https://github.com/saif-ali/nagios/blob/master/thursday_user_network.png?raw=true)  

- webopac.iitmandi.ac.in  

![ping Students](https://github.com/saif-ali/nagios/blob/master/thursday_ping_webopac.png?raw=true)  

##### Friday : (8:00 am to 2:00 pm)

- students.iitmandi.ac.in  

![cpu Students](https://github.com/saif-ali/nagios/blob/master/friday_cpu_students.png?raw=true)
![ram Students](https://github.com/saif-ali/nagios/blob/master/friday_ram_students.png?raw=true)
![ping Students](https://github.com/saif-ali/nagios/blob/master/friday_ping_students.png?raw=true)
![user Students](https://github.com/saif-ali/nagios/blob/master/friday_user_students.png?raw=true)  

- insite.iitmandi.ac.in  

![cpu insite](https://github.com/saif-ali/nagios/blob/master/friday_cpu_insite.png?raw=true)
![ram insite](https://github.com/saif-ali/nagios/blob/master/friday_ram_insite.png?raw=true)
![ping insite](https://github.com/saif-ali/nagios/blob/master/friday_ping_insite.png?raw=true)
![user insite](https://github.com/saif-ali/nagios/blob/master/friday_user_insite.png?raw=true)  

- network.iitmandi.ac.in  

![cpu network](https://github.com/saif-ali/nagios/blob/master/friday_cpu_network.png?raw=true)
![ram network](https://github.com/saif-ali/nagios/blob/master/friday_ram_network.png?raw=true)
![ping network](https://github.com/saif-ali/nagios/blob/master/friday_ping_network.png?raw=true)
![user network](https://github.com/saif-ali/nagios/blob/master/friday_user_network.png?raw=true)  

- webopac.iitmandi.ac.in  

![ping Students](https://github.com/saif-ali/nagios/blob/master/friday_ping_webopac.png?raw=true)

##### Sunday : (8:00 am to 2:00 pm)

- students.iitmandi.ac.in  

![cpu Students](https://github.com/saif-ali/nagios/blob/master/sunday_cpu_students.png?raw=true)
![ram Students](https://github.com/saif-ali/nagios/blob/master/sunday_ram_students.png?raw=true)
![ping Students](https://github.com/saif-ali/nagios/blob/master/sunday_ping_students.png?raw=true)
![user Students](https://github.com/saif-ali/nagios/blob/master/sunday_user_students.png?raw=true)  

- insite.iitmandi.ac.in  

![cpu insite](https://github.com/saif-ali/nagios/blob/master/sunday_cpu_insite.png?raw=true)
![ram insite](https://github.com/saif-ali/nagios/blob/master/sunday_ram_insite.png?raw=true)
![ping insite](https://github.com/saif-ali/nagios/blob/master/sunday_ping_insite.png?raw=true)
![user insite](https://github.com/saif-ali/nagios/blob/master/sunday_user_insite.png?raw=true)  

- network.iitmandi.ac.in  

![cpu network](https://github.com/saif-ali/nagios/blob/master/sunday_cpu_network.png?raw=true)
![ram network](https://github.com/saif-ali/nagios/blob/master/sunday_ram_network.png?raw=true)
![ping network](https://github.com/saif-ali/nagios/blob/master/sunday_ping_network.png?raw=true)
![user network](https://github.com/saif-ali/nagios/blob/master/sunday_user_network.png?raw=true)  

- webopac.iitmandi.ac.in  

![ping Students](https://github.com/saif-ali/nagios/blob/master/sunday_ping_webopac.png?raw=true)

---