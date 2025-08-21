# AndroidStudioInventoryApp

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The Inventory App lets users track items in a database. This has many business use cases such as using it to keep track of items in a warehouse, store, an e-commerce site, etc.
This app lets users add, update, remove and view items in their database. It also has a log in system which will persist previously stored data with the SQLite database.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The screens that were needed for features involving the UI included: a login screen, a grid to display inventory, and a permissions screen. Keeping the design of the login screen kept it simple for users as they can type in their username and password to log in. If they did not have an account, they can click the create account button allowing them to utilize the inventory service. Keeping the inventory in a grid allowed for easy viewing of items. There are two buttons within an item's row allowing the user to easily update or remove an item. Towards the buttom of the screen a user can enter an item's details and then click add to the grid. Text hints were created here so users can easily read the prompt and know which input is needed.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
Working backwards from the UI, the UI screens were made first. I then added activites and xml files to correspond which each activity. I used the Main Activity to link most of the screens together when the on create was activated. I also used on click listeners in order to initiate the activities or switch screens. Creating the UI with the user in mind can be used in the future to anticipate how the screen will look and how features need to be connected to different buttons or sensors.

## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
As I changed small snippets, I ran the program every few minutes to ensure nothing broke. When I made breaking changes, I often viewed my local code history to see what mistakes I may have made or what had been added and needed revision. This is important because the wrong punctuation or syntax can break the entire app. When trying to add something I was unfamiliar with there was a few times I had to remove features to keep functionality.
