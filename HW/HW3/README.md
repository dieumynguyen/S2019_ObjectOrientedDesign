<b>HW 3:</b> Hardware Rental Store

<b>Due:</b> 01 March 2019

<b>Team member(s):</b> Dieu My Nguyen, Adil Sadik, Yu Li

<b>Assignment description:</b> Write an object-oriented program that implements the problem domain and does the following:
- Simulates the activity of the rental store for 35 days (34 nights). On each day, a random
number of customers will visit the store as long as there are tools to rent. Each customer
will create one Rental that follows the rules of their associated type before they leave the
store. That is, no customer will show up and then leave without making a rental. Note: if
the store has less than 3 tools, then a Business customer will NOT arrive (as they
wouldn't be able to create a Rental that follows their rules). As soon as the store has
zero tools, customers will magically stop arriving until tools are once again available.
- At the end of the simulation, the program will produce a report that includes the following
information:
  - the number of tools currently in the store along with a list of their names
  - the amount of money the store made during the 35 days (including any rentals
  that occurred on the 35th day)
  - a list of all the completed rentals including which tools were rented by which
  customer for how many days along with the total amount of that rental
  - a list of all the active rentals that includes all of the information listed in the
  previous bullet
- A customer can have more than one active rental. That is, they can show up on day 1
and rent 1 tool for 5 nights. They can then show up on day 2 and rent another tool for 4
nights. As long as they do not have more than 3 tools rented, they are allowed to have
multiple rentals.
- Returns occur at the beginning of the day before the store opens for business. A tool
rented for one night is available to customers the very next day; that's because the
customer rented the tools for one night, used it, and got it back to the store early the next
morning.
- Your program should be single-threaded; you do not need to handle the case of multiple
customers trying to rent tools concurrently.

<b>Instructions to run code:</b> Simply run the Python code cells in the Jupyter Notebook. Cells are pre-run to show sample report output.
