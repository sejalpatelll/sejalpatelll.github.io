To link the google sheets to website (https://www.youtube.com/watch?v=0YFrGy_mzjY):
1. Create a google sheets with a proper title
2. Go to Extensions --> Apps Script
3. Title it the same thing as your google sheets
4. Copy and paste the code from the google script file in the repository 
  link: https://github.com/jamiewilson/form-to-google-sheets
5. Run the code, click 'review permissions', sign in google account, click 'advanced', click 'go to contact form(unsafe)', click 'allow'
6. Click 'deploy' at the top right, click 'new deployment', click on setting icon then 'web-app', add a description and make sure to select 'anyone' for who has access section, then click 'deploy'
7. Copy the URL that will appear under Web App 
8. Go back to GitHub Link and scroll down to find script 
9. Copy and Paste the script into the HTML file and also paste the link that you got from the Google Sheets into the section for URL in the script
10. Copy the form text ('submit-to-google-sheet') and paste it like this whereever your form is: '<form name="submit-to-google-sheet">'
11. Test to see if it works