# AppointmentSystem

This is a simple appointment system created using Django rest framework and Angular.

## Features



1. Automatically generated available timeslots. (not implemented yet)
2. User friendly interface for booking and managing appointments. (not implemented yet)
3. Reduce work by using repeated business hours. (not implemented yet)
4. Close certain weekdays and dates. (not implemented yet)
5. Dashboard to easily manage and see appointments and details of page. (not implemented yet)
6. Every user can create own appointment page with own services and times. (not implemented yet)
7. Email notifications for booking confirmation and customizable reminders. (not implemented yet)
    - System will send email notification to the customer confirming the appointment. (not implemented yet)
    - System will send email reminder to the customer 24 hours or specified time before the appointment. (not implemented yet)
8. Prebooking appointment for 30 minutes as `pending` to prevent other people from booking the appointment before the customer has given all of the required information. (not implemented yet)
9. Cancel appointments (not implemented yet)
    - System will send email to the customer confirming cancellation. (not implemented yet)

## Running the application

To be able to run the application you have to have angular version 19.1.2 and django version
5.1.3.

To be able to run the application you have to install the packages needed and setup the django settings to run the code.

### Python

Install python packages using requirements.txt file.

```pip install -r requirements.txt```

You have to be in the backend folder to be able to do this.

### Angular

Install angular packages using npm.

```npm install```

You have to be in the frontend folder to be able to do this.

### Running angular

You can now run angular application.

```ng serve```

after that you can navigate to localhost:4200 in your browser and