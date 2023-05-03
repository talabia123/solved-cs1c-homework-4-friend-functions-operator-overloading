Download Link: https://assignmentchef.com/product/solved-cs_1c-homework-4-friend-functions-operator-overloading
<br>
Using HW03 …

<ol>

 <li>Write and test a friend function that checks to see if the phone number of a C1SCEmployee object is equal to the phone number of a Programmer object. Test equal and not equal scenarios. (You will need to call your ChangePhoneNumber method)</li>

 <li>Overload the equality operator to see if the phone number of two C1SCEmployees are the same. Test equal and not equal scenarios. (You will need to call your ChangePhoneNumber method)</li>

 <li>Write an addition member function that adds an integer to a CS1Cemployee’s age (make sure the integer is a passed parameter). The output should state how many years were added to the age.</li>

 <li>Overload the addition operator to add a constant to a</li>

</ol>

CS1Cemployee’s age. For example: StarC1SCEmployee = StarC1SCEmployee + 2.  The output should state how many years were added to the age.

<ol start="5">

 <li>Overload &lt;&lt; and &gt;&gt; operators to read in a CS1Cemployee object</li>

</ol>

(e.g. cin &gt;&gt; myEmployee and cout &lt;&lt; myEmployee)

Your output should be easy to follow and contain output only from hw04.

Extra Credit [+5 pts]

Overload the pre &amp; post increment operators to increment an

CS1Cemployee’s age. Test pre/post increment operations. Output HW04 – Friend Functions &amp; Operator Overloading [50 pts]

the values of CS1Cemployee objects before and after pre/post increment operations as well as after assignment takes place.

Demonstrate how pre/post increment operators are different.

Which overloaded operator incurs the most overhead?

Use the command script to capture your interaction compiling and running the program, including all operations, as shown below:

CS1C Fall 2018 TTH HW04 50pts <strong>Due: Tu 9/11/2018 </strong>

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="395a4a085a795a4a085a146f504b4d4c58557b5641">[email protected]</a> ~/cs1c/hw/04 $ script hw04.scr Script started, file is hw04.scr <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="8ae9f9bbe9cae9f9bbe9a7dce3f8feffebe6c8e5f2">[email protected]</a> ~/cs1c/hw/04 $ date

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="9dfeeeacfeddfeeeacfeb0cbf4efe9e8fcf1dff2e5">[email protected]</a> ~/cs1c/hw/04 $ ls -l

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="3b58480a587b58480a58166d52494f4e5a57795443">[email protected]</a> ~/cs1c/hw/04 $ make all

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="f49787c597b49787c597d9a29d8680819598b69b8c">[email protected]</a> ~/cs1c/hw/04 $ ls -l

…

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="93f0e0a2f0d3f0e0a2f0bec5fae1e7e6f2ffd1fceb">[email protected]</a> ~/cs1c/hw/04 $ ./hw04




… // print out test results for the friend &amp; member functions from steps 1, 3

… // print out test results for the overloaded operators from steps 2, 4, 5




<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="1a79692b795a79692b79374c73686e6f7b76587562">[email protected]</a> ~/cs1c/hw/04 $ exit Script done, file is hw04.scr

<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="d4b7a7e5b794b7a7e5b7f982bda6a0a1b5b896bbac">[email protected]</a> ~/cs1c/hw/04 $ make tar

…