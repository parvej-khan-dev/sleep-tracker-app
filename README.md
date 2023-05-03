# Introduction

Irregular sleeping patterns are a common problem. This web app will fulfill the user's needs in tracking their sleeping patterns, including duration and timings. You will create a web app to track three parameters: sleep time, wake up time, and sleep duration. Users can add, edit, or remove any sleep entries.

## Requirements

### Front-end & UI Design
* Splash Screen: When a user is not logged in, show the homepage with an introduction of the app and how it can help users track their sleep better.
* Signup page: Use Google or Facebook libraries or implement your own authentication module.
* Login page: a user should be able to login to the account using their signup method.
* New user login: show an empty page with the “New entry” button. Once the user clicks “New entry,” show a modal dialogue/popup:
Select date using date picker
* Select sleep time in hour and minutes
* Select wakeup time in hour and minutes
* Calculate total sleep duration
* Include reset, cancel, and submit buttons
* Old user logs in: show a list of entries for the last 7 days or 1 month
* The list should include: date, time of sleep, wake up time, and sleep duration
* Use graph libraries to show a floating bar chart with the Y axis as the sleep duration and X axis as dates
Show a “new entry” button

### Back-end

* All entries must be stored in persistent storage on the server where it can be fetched at any time. Use databases and Rest APIs to fetch the data.
* Write backend APIs to read, write, and update entries.
The following image shows one way to implement the UI. Feel free to interpret the requirements however you'd like!

![](https://ucarecdn.com/ff87204a-bacb-42e9-ad45-6b8623b57d6b/)

**Extra challenge**: Add more visualization for weekly and monthly analysis

 * Average sleep duration for the week
* Number of days the user slept less than 6 hours
* Number of days the user slept more than 8 hours
* Average sleep and wake up time


## License

[MIT](https://choosealicense.com/licenses/mit/)
