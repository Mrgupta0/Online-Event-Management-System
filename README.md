# Online Event Management System (Core Java + Collections)

Simple console-based CRUD project implemented in core Java using Collections (ArrayList, HashMap).

## Features
- Manage Events (Create, Read, Update, Delete)
- Manage Users (Create, Read, Update, Delete)
- Manage Bookings (Create, Read, Cancel)
- Console menu-driven UI

## How to compile & run
1. Make sure Java (JDK 8+) is installed.
2. From the `src` folder run:
   ```
   javac com/oems/*.java com/oems/model/*.java com/oems/repo/*.java com/oems/service/*.java
   java com.oems.Main
   ```
3. Alternatively, open with any Java IDE (Eclipse/IntelliJ) as a plain Java project.

## Structure
- src/com/oems/Main.java
- src/com/oems/model/{Event,User,Booking}.java
- src/com/oems/repo/{EventRepository,UserRepository,BookingRepository}.java
- src/com/oems/service/{EventService,UserService,BookingService}.java

