# Full Stack Developer - Technical Task

Thanks for applying to work at FATMAP. We have developed this small task for you to work on in your own time so that we can see how you approach tasks and as a discussion point going forwards.

Try to spend less than two hours on this task - and don't worry if it is not complete, we prefer to see quality over quantity.

It's totally up to you how to implement the solution, feel free to use the language you feel most comfortable with and any frameworks that you prefer to use.

## The task

Using the off-pistes.json (this file contains the off-piste lines in Chamonix) file in this repo, build a service/API that has endpoints do the following.

* Allow searching of an off-piste line by name or partial name.

* Allow filtering and sorting of off-piste lines by ski_difficulty

* **Bonus task**: Create an endpoint that takes an id param and returns an HTML Canvas object containing the line so that the line could be previewed in a browser. Hint: the data format is [Long, Lat, Elevation] - you can ignore elevation for this.

### Notes

* For the above the service should return JSON with id, name, description and ski_difficulty fields.

* You don't need to create a front-end for this, bonus marks if you do.

* Please create documentation for the steps required to run the project and to access the API. 
