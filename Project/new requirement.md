# new requirement for Topic 1
## Double 11 campaign 

Your client Mr Clint called your project manager on Friday night and said that they have an urgent issue wants your team to follow up. They start realizing double 11 is a big things in Hong Kong now. They want to do the following task. If your team is able to finish the task before next Milestone, Mr Clint will be very happy and may give you some more rewards. 

> Employee can offer some seats with special discount at a particular time for customers to compete (the earlier one who response will get the seat). 
>
> Take an example, the tour 2D00120171111, an employee can set 6/11 9am and send out the message to all clients. The first four clients replies can have a discount rate (50% off) for that tour. Each client can reserve 2 seats at most. After that any client who response will read "Sorry ticket sold out".

For groups that do not implement web interface, you can inject this special discount offer into the database directly using psql command line command or any other means. For groups that implements web interface, you need to also create an web interface for employee to input this event.

# new requirement for Topic 2 
## New user booster

Your marketing department had just finished a meeting with the hostile boss which was very angry about the number of users is very low (of course, the app has not launched yet, but she did not care). The head of marketing came up with a new proposal and just got approved in the meeting -- run a campaign to boost up the number of users as follows. If your team is able to finish the task before next Milestone, the entire marketing team will be very happy and may agree to give you some rewards (e.g. have a date with all your team members, or just some points to your project).

> Each current user can type "friend" into the chatbot and the chatbot will reply them a 6-digits unique code. The user can give this code to his friend and recommend them to add the chatbot as their line friend. The new user then type "code" into the chatbot followed by the 6-digits unique code, then the chatbot will send an ice-cream store electronic coupon to both of the new user and the old user. Each new user can claim the coupon once only. Each user can recommend infinite number of friends. Each new user can also recommend new users. Users who registered before the campaign cannot type "code" to get the coupon. After 5000 copies of ice-cream coupon were given out, the campaign stops.

For H-group you will need to allow an admin to upload the coupon image via LINE directly, with a special command that only avaliable to particular account. For non H-group, you can simply place the coupon image as a static resource.

# new requirement for Topic 3
## Thanksgiving Party

After half semester your freshmen friends seems learned a lot from statistics class, because they keep talking about mean and SD. Your team decided to have a thanksgiving party to cheer them up (this year thanksgiving is on 23rd Nov, btw). Freshmen are invited to this party and they will need to bring some snack food. Your team is going to complete the following things with your chatbot. If the freshmen are happy they can do well in the final and some group in COMP3111 will also receive more points.

> All freshmen users will receive a thanksgiving party invitation poster in the chatbot daily (from 21 to 27 of Nov <-- for us to grade) until the user type "accept". Then he will need to enter what party snack he will bring. The bot replies either "1) Great, please prepare 5 people portion of that". or "2) Someone is bringing that already, can you pick another one?" (reply this if some other people pick that food already). One day before the party a reminder should be sent to all people who is going.

For H-group you will need to allow an admin to upload the poster via LINE directly, with a special command that only avaliable to particular account. For non H-group, you can simply place the poster image as a static resource.
