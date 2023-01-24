# X-Booking-Web-Application-Report

## Guide By
- Dr Mohd Khairul Azmi B Hassan

## Prepared By
- Fatina Mukhammadalieva Azam Kizi 1920218
- Muhammad Fayyadh Khumaini bin Khamsani 2112233
- Ameer Al Wafiq Bin Norazam 2119005
- Robbani Ghozi Fikri 1832765 

# X-Booking System

## Introduction
The web application of Booking System in a gaming company named "FlashPoint Studio" is an innovative and convenient solution that allows customers to book a provided place for them to play their favorite games. With the help of this system, customers can easily browse through the available options, select their preferred date and time, and make a booking with just a few clicks. 

One of the key benefits of the Booking System is that it allows customers to plan and schedule their activities in advance, ensuring that they can enjoy their favorite games and activities without any delays or disruptions. The system also helps the company to manage its bookings and resources more efficiently, as it allows them to keep track of the availability of their games and activities in real-time. The system is user-friendly and intuitive, making it easy for players to find and reserve the time slots that best suit their schedules. Players can simply select their preferred location, game, and time slot, and our system will automatically confirm their booking. 

In addition to its convenience and efficiency, the Booking System also offers a range of additional features that make it an attractive solution for both customers and the company. These include the ability to view and cancel bookings online, receive notifications about upcoming activities, and access special offers and discounts. By allowing players to reserve time slots in advance, we can ensure that all of our gaming stations are being used to their full potential and minimize the risk of overcrowding. 

Overall, the web application of Booking System in FlashPoint Studio  is a valuable tool that helps the company to improve its customer experience and streamline its operations. By offering a convenient and user-friendly way to book games and activities, the system helps to attract and retain customers, while also enabling the company to better manage its resources and optimize its revenue. We are confident that this new web application will greatly enhance the gaming experience for our players and help to make their visits to FlashPoint even more enjoyable. 

## Objective
At FlashPoint Studio, we are always looking for ways to improve the gaming experience for our players. That's why we have recently developed a new web application for booking systems.

Our main objective in creating this web application was to streamline the booking process for our players and make it more convenient for them to reserve time slots for their favorite games at any of our locations. We wanted to create a system that was easy to use and intuitive, so that players could find and reserve time slots with minimal effort.

Another key objective of our booking system is to help us better manage and utilize our resources. By allowing players to reserve time slots in advance, we can ensure that all of our gaming stations are being used to their full potential and minimize the risk of overcrowding. This will help us to provide a better gaming experience for all of our players, as well as maximize the efficiency of our operations.

In addition to these core objectives, we also wanted our web application to be visually appealing and user-friendly. We wanted to create an interface that was easy to navigate and provided all of the necessary information in a clear and concise manner.

## Features and Functionalities
- Home Page: Browse easily the details of the company, the features available such as the media, products and the accesibility to login and make a booking.  

- Register & Login: Provide your personal details and create a unique username and password to be able to book a station.

- Booking Page: Navigate to the booking page and select date, time, and the station you wish to book.

- Payment Page: Making a payment according to the price and through QR code provided.

## Sequence Diagram
![unnamed (1)](https://user-images.githubusercontent.com/120077901/214079866-aaf6a43f-4a85-4152-8efb-151ff1d53702.png)

## Project System Captured Screen
### Main Page
![main page](https://user-images.githubusercontent.com/120077901/214209748-ed49f670-b0d0-4db9-9d37-2dd9fd51ff6c.jpg)

This picture shows an interfaace and design to introduce to the company and its services and products. Besides that, It has a navigation button to bring the user to register, login and Booking (for the registered user).

### Register & Login Page
![register page](https://user-images.githubusercontent.com/120077901/214210055-af6a8749-cced-424d-977a-f4145197e05f.jpg)

This picture shows an accesibility to login and register. We used Jetstream for this feature because it s reliable for authentication.

### Booking Page
![booking page](https://user-images.githubusercontent.com/120077901/214209789-696257fb-1458-4938-af72-8eccf5d8cb7d.jpg)

This picture show sections of input where user kan enter Date, Time, Duration and Number of controllers according to the price list that is provided.

### Payment Page
![payment page1](https://user-images.githubusercontent.com/120077901/214209799-e50b917d-a47f-4aad-86f6-4771b621e2ab.jpg)
![WhatsApp Image 2023-01-24 at 03 32 26](https://user-images.githubusercontent.com/120077901/214209815-d8b3bfd9-1a32-406c-b370-b34b22086fd6.jpg)

This picture shows a payment page where user can proceed with payment by scanning the QR code and it will promted to next page for the user to share receipt in the WhatsApp


## Challenges/Difficulties in Develop the Application
- Unable to create a log out feature outside of Jetstream because there are unidentified codes which we unfamiliared to modify the Jetstream. Instead, We included the Jetstream DashBoard which has logout feature in our system.
- The difficulties to record a data in Booking Page to generate the calculation of price and record data due to complications in Routing and Controller. 
