# Groupbuybot

##Commands:

/groupbuy - Initiates the group buy and registers the user as the admin.
/setprice {price} - Sets the price for the group buy.
/setcurrency {usd, euro, cad} - Sets the display currency (for visual purposes only).
/setdescription {description} - Sets a detailed description for the group buy.
/setdays {days} - Sets the duration of the group buy in days. Once the deadline is reached, no further participants can join.
/setlink {link} - Sets the join link for the group buy.
/clear - Clears the current group buy, allowing for a new person or a new group buy to start.
/paid {usernumber} - Sets the payment status of a specific user to "paid."
/setallpaid - Sets the payment status of all users to "paid."
/notpaid {usernumber} - Sets the payment status of a specific user to "unpaid."
/setallnotpaid - Sets the payment status of all users to "unpaid."
/unpaid - Mentions all buyers who have yet to pay.
/remove {usernumber} - Removes a specific user from the buyer list.
/kickunpaid - Removes all members who have joined the group buy but have not paid.
/donate - Get a donation link to help keep the bot running and fund new functionalities.

##Notes:
The /setcurrency command is for display purposes only and does not affect any other functionalities.
The /setdays command determines the duration of the group buy, and after the deadline, no new participants can join.
Use the /clear command to reset the group buy for a new cycle.
Ensure accurate use of user numbers when applying commands for individual users.

For support or suggestions, leave them in the GitHub page or contact @SheepGod on Telegram
