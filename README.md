# first-slcb
A Streamlabs Chatbot (standalone) script which will reward viewers for attending the start of a stream and using a command. Original concept by Must13.

To-do:

(1) Give the user the ability to define how many winners they'd like to reward. This will allow the system to scale to whatever audience size the user would prefer, but will also make it necessary to completely rebuild the script.

(2) Create a button which will auto-populate reward values between #2 and the number of reward winners defined by the user. They'll have to enter an intended reward amount for first place before clicking this button, and it'll apply a formula to that value to determine diminishing return reward values for every other winner.

(3) Create a button which will open the reward values file for manual editing. The Streamlabs Chatbot UI is going to be very cumbersome for manual editing, so it'll be recommended for users to simply use the auto-populate button. If they want to customize each value, they'll need to do it from the rewards file.

(4) Related to #3, remove the UI elements for customizing reward values and responses for second-and-later users. Change the default response verbage to be more appropriate for a potentially large, variable number of rewards. For example, instead of saying they're 'second' and 'third' perhaps we'll just say "$user you were in position number $position and earned a reward of $reward!"
