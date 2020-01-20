# Tool choice 

I chose the tool Postman, because I already had heard about this tool from the developers and just once I made a manual test sending some requests. It seemed to me easier to get familiarize with the tool.

I know for REST API Tests there is Postman and Soap UI.
These are basically the only tools that I have heard.

I chose javascript, because so far I mostly have worked with javascript and has done UI Automation.
It is the first time that I am automating REST APIs and it took me a while to get familiarize with the logic.


## Run the tests

1)Install Postman and create and Account
2)Choose from the Menu on Top Import and choose the option import from link
3)Paste the provided link by me there.
:https://raw.githubusercontent.com/manerafilo/example-sharing/master/assignmentNew.json
4)Run each request

## Notice

I tried to write as many tests as possible for each scenario, if you happen to need new IDs for put, patch and delete requests, I already created some more bookings with the Post request.

## IDEAS 

So I created 9 requests
3 GET for getBooking
1 POST to create Booking
1 PUT for Update Booking
1 PATCH for Partially Update Booking
1 DELETE for Delete Booking
1 POST for Authorization
1 GET for health Check

I have to repeat that I had zero idea about Rest API Automation and had to learn everything from scratch and tried to cover as many scenarios as possible, I wanted to do more, but I don't have that much time unfortunately.
P.S:All tests were green.
