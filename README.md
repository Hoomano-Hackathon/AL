Reminders and Memory game for alzheimers sufferers

This project consists of two applications:
* A memory game to help remind people about their families
* A reminder application driven by google calendar


Calendar format
---------------
The reminder application is driven by google calendar (currently the calendar ID is hard-coded, this needs to be fixed) The application looks for the next event within 30 minutes and uses the start time and description to drive the nature of the reminder)

The grammar for the description field is:
* Wake
* Meal|{Mealtype} where Mealtype can be Breakfast, Lunch or Dinner
* Visitor|family|{person name}|{relationship}
* Visitor|doctor
* Visitor|helper
* Medicine
* Sleep
