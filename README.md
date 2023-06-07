## HELP_DOCUMENT For C-MONEY

### Login and Register
- User has to use a valid email and passowrd for sign up and login to the app.
- The length of password should at least has 6 digits.
- The credential information is handled by `Firebase`.
- Currently user not able to delete their account manually, please contact the admin if you do not want the account any more.

### Home page
- The `Expenditure` chart will not include the records belong to `Income` category.
- Tap on the segmented button to see the chart in different time intervals `Daily`, `Weekly` and `Monthly`.
- Download button at top right corner requires permission of adding photo to album, and we do not require viewing photo permission which garanteed the privacy of user.
    - *Note: Download button will also save the image as pdf and you should be able to view it through document reader.*

### Record page
- User can search the record by using the `note` through top search bar.
- Tap on each record to see the full details and opeartions (delete and modify the record).
- The order of records is based on the `Record Creation Time`.

### Adding record page
- If the location permission is given, user can tap on the icon button at the end of location input field to get the current position.
- Users are allowed to create their customised categories for records.
    - *Note: customised categories are stored in local which means they will disappear if you reinstall or wipe the data of app*

### Adding saving page
- If the notification permission is given, user will receieve the notification if they are closing to their target `above 90% progress`. On fixed time period. `Notification will be pushed on Friday 7pm`.
- Each user only can create one saving goal at one time, delete the old one if you want create a new saving goal.

### Setting page
- Notification is on by default, and you can turn it off if you do not want to be interrupted.
- Darkmode within the app is available and there are total of four different themes can be choose as you like.
- You can also change you password through login setting.

---
### **FAQ**
Q: I forgot my password how can I find it back?

A: On login page you can enter your email and then tap on `Forgot password` button at the bottom of screen. A rest password link will be sent to your email and you could use new password to login after reset it.

Q: The app asks me to reopen it and login again?

A: It is possible that you reinstalled app and trying to login with an existing account. Due to security issue you have to reopen the app and login again `This only required after reinstalled the app`

Q: How to contact the admin?

A: Please contact through email `fzl844739905@gmaill.com`.
