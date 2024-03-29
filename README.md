# Truecaller_automation
**Fetching data from the website using web driver**

This Python script is designed to automate the process of logging into the Truecaller website, searching for a phone number, and extracting information. 
It uses the Selenium library to interact with the website and perform these tasks.

Here's a breakdown of what the code does:

1. It sets up a web driver using ChromeDriverManager, which allows it to control a web browser.

2. It navigates to the Truecaller website and maximizes the browser window.

3. The code clicks on the "Sign in" button on the Truecaller website.

4. After clicking the "Sign in" button, it clicks on the "MICROSOFT" option to sign in using a Microsoft account.

5. It enters your Microsoft email address and password in the respective input fields.

6. It clicks on the submit button to log in.

7. The code then clicks through some additional prompts or pop-ups.

8. It locates the search input field and enters a mobile phone number to search for.

9. It clicks the search button to initiate the search.

10. After a delay, it extracts and prints the name and email associated with the phone number.

Finally, the script quits the web browser.

This code is a helpful tool for automating the process of searching for information on the Truecaller website using a Microsoft account. 
Make sure to replace the placeholders (like email, password, and phone_number) with your actual credentials and the phone number you want 
to search for before running the script.
