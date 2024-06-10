![image](https://github.com/Mpilorh05/Weather-App/assets/140204693/c43be15d-6abc-425a-8eb2-225f606a902a)# Weather-App
MPILO CHILI-ST10436955
https://github.com/Mpilorh05/Weather-App
The app basically allows for users to login into an app called Weather App, then when proceeding to the main screen user are therefore permitted/make use of calculations of weekly weather forcast
Pseudo Code                                                                                                                                                                                 START                                                                                                                                                                              
Declare days[0] = "Saturday"
Declare days[1] = "Sunday"

Declare temperatures[0] = 25 // example temperature for Saturday
Declare temperatures[1] = 28 // example temperature for Sunday

Declare details[0] = "Sunny with light winds" // example detail for Saturday
Declare details[1] = "Partly cloudy with a chance of rain" // example detail for Sunday
Display "Welcome to the Weekend Weather App"
Display "1. View Average Temperature"
Display "2. View Detailed Information"
Input choice
If choice == 1:
    Call displayAverageTemperature()
Else if choice == 2:
    Display "Enter the day (Saturday/Sunday):"
    Input day
    If day == "Saturday" or day == "Sunday":
        Call displayDetails(day)
    Else:
        Display "Invalid day entered."
Else:
    Display "Invalid choice entered."
    End
