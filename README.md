# Twitter-Timeline Challenge
Create a small PHP-script to accomplish following parts:

# Part-1: User Timeline

- Start => User visits your script page.
- User will be asked to connect using his Twitter account using Twitter Auth.
- After authentication, your script will pull latest 10 tweets from his “home” timeline.
- 10 tweets will be displayed using a pure CSS and Plain JS slideshow.
# Part-2: Followers Timeline

- Below slideshow (in step#4 from part-1), display list 10 followers (you can take any 10 random followers).
- Also, display a search followers box. Add auto-suggest support. That means as soon as the user starts typing, his followers will start showing up.
- When user will click on a follower name, 10 tweets from that follower’s user-timeline will be displayed in the same slider, without page refresh (use AJAX).

# Part-3: Download Followers

- There will be a download button to download all followers of any user(we will input user @handler).
- Download can be performed in one of the following formats i.e. You choose the format you want. It would act as an advantage if you give the option to download the followers in all the following formats:
google-spreadsheet, pdf and xml formats.
- For Google-spreadsheet export feature, your app-user must have Google account. Your app should ask for permission to create a spreadsheet on user’s Google-Drive.
-Once the user clicks download button (after choosing option) all followers of the specified user should be downloaded.

# Demo link
  [Demo](http://twitter.alampatawebsolution.a2hosted.com)

# Links to libraries
- php library: https://github.com/abraham/twitteroauth
- google drive library: https://developers.google.com/drive/api/v3/quickstart/php
- PDF library: https://github.com/tecnickcom/tc-lib-pdf 
- Excel library: https://github.com/PHPOffice/PHPExcel
- jQuery: https://jquery.com
# Plugin that I have used
- carousel bootstrap slider, I take it from https://startbootstrap.com/template-overviews/full-slider/ . and I have done some custom css.
- There are to searchbox in my demo site, A searchbox in my header i have used autosearch from https://jqueryui.com/autocomplete/ and seacond searchbox i have done by myself.

# Used MVC:
- model.php has all function,controller.php works as route and view.php contains view code.

# Used custom css:
- I have used custom css in place of boostrap and tried to make application responsive.(in slider i have used custom css+ bootstrap).


