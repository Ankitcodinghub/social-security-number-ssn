# social-security-number-ssn
**TO GET THIS SOLUTION VISIT:** [social security number (SSN)](https://www.ankitcodinghub.com/product/social-security-number-ssn/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;6360&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;social security number (SSN)&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
<div class="product-description">Your program should prompt a user to enter a social security number (SSN) as a series of digits.

It will check whether the user entered a valid 9-digit SSN and report an error message if the SSN entered is too short or too long or if the user enters a non-numeric input.

It should report a specific error message for each of the three possible errors listed in the bullet point above.

If the user makes a mistake, the program should re-prompt the user using a loop (suggestion: do-while loop).

Once the user enters a valid input, the program will display the SSN in the the format XXX-XX-XXXX

You are required to write a function with the following signature to check whether the user entered a numerical SSN (i.e. whether all of the digits entered were numerical). If the user enters any other character besides 0-9, return false, otherwise return true. Hint: Use ASCII

Copy and paste the below prototype&nbsp;above&nbsp;main and then write the function&nbsp;below&nbsp;main.

bool isNumeric(string SSN);//use ASCII to determines if a string contains only the characters 0-9You are also required to have a function with the following signature to display the SSN.

Copy and paste the below prototype above main and then write the function below main.

void displayFormattedNumber(string SSN);

//Calls the formatSSN function and then displays it to the console

//With the message “You entered: ” followed by the SSN

string formatSSN(string SSN);

//helper function to displayFormatted SSN

//converts a 9 character string into an SSN in the format XXX-XX-XXXX

Your program should work identically to example below:

Please enter a 9-digit SSN (no spaces no punctuation): 12345

You entered too few digits. Please try again.

Please enter a 9-digit SSN (no spaces no punctuation): 123456789012345

You entered too many digits. Please try again.

Please enter a 9-digit SSN (no spaces no punctuation): 123 456

You entered too few digits. Please try again.

Please enter a 9-digit SSN (no spaces no punctuation): 123 456 7890

Please enter a number with no spaces or punctuation. Please try again.

Please enter a 9-digit SSN (no spaces no punctuation): 123-45-6789

Please enter a number with no spaces or punctuation. Please try again.

Please enter a 9-digit SSN (no spaces no punctuation): 123456789

You entered: 123-45-6789

It is strongly suggested to structure your main function like this:

bool not_valid_SSN = true;

do {

//user input

if (test for too short) {

//display appropriate error message

} else if (!is_numeric(SSN)) {

//display error message

} else if(test for too long) {

//display appropriate error message

} else {

//display appropriate formatted phone number

not_valid_SSN = false;

}

} while(not_valid_SSN);

</div>
<div class="ui divider"></div>
