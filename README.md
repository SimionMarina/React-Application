# React-Application

Application Name: “FlatFinder” using React,JavaScript and Firebase

Environments
• Browser.
• Responsive: Desktop, Tablets, and Smartphones.

Technologies
• UI: HTML, CSS, JavaScript, React
• Data Base Server: Firebase

Entities
•User (Name, Email, Password, Birth Date)
•Flat (City, Street name, Street number, Area size, Has AC, Year Build, Rent price, Date available)
•Message (Content String, Creation time)

Pages

1. New Flat
   • Inputs for all flat’s properties as specified in the entities section.
   • Save button.
   If all inputs are valid then the data will be saved. After a successful update, the user will be
   redirected to his home page.

2. Flat View
   This page shows all the properties of a given flat that are specified in the entities section.
   In case the user is the owner of the flat entry then he will have a button that redirects him
   to the editing page.

3. Messages
   If the user doesn’t own the flat entry then he can send a message to the owner about the
   given flat. Someone who doesn’t own the flat will see in this page only his own messages.
   The owner will see all the messages that others sent him about the given flat. For the sake
   of simplicity, the owner doesn’t have the option to send back a message. Every message will
   contain the following:
   • Creation time stamp.
   • Sender's full name and email.
   • Message content.

4. Edit Flat
   • Inputs for all flat’s properties as specified in the entities section.
   • Update button.
   If all inputs are valid then the data will be saved. After a successful update, the user will be
   redirected to his home page.

5. Home
   This page contains a table of all the flats that are stored in the system. Each row in the table
   will hold the following:
   • All of the flat’s properties as specified in the entities section.
   • Link/Button to open the flat view page.
   • Toggle button to mark/unmark as favourite.
   • Owner’s full name and email.
   In addition, the table will have filtering and sorting capabilities.

6. My Flats
   This page allows a user to manage the entries of flats that he publishes in the system. The
   page contains the following:
   • Insert new flat button.
   • Table of all the users’s flats. Each row will hold the following:
   – All of the flat’s properties as specified in the entities section.
   – Delete button.
   – Link/Button to open flat view.
   – Edit button/link.

7. Favourites
   This page contains a table of all the users’s favourite flats. The table structure will be the
   same as the one in the home page besides a single distinction: instead of a toggle button,
   each row will have a remove button. After pressing it the flat will be removed from the
   table and won’t be considered to be one of the renter’s favourite.
