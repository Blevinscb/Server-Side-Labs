# Server-Side-Labs
Just the labs for the class Server Side Prog 
Star Wars Info Viewer

This C# Console Application enables users to engage with the Star Wars API, facilitating the retrieval and presentation of details concerning characters, episodes, and locations from the animated "Star Wars" movie series."

ISSUES ENCOUNTERED PLUS SOLUTIONS
Challenges Faced and Resolutions Implemented Challenge 1: Retrieving Character Information Error Description: The application encountered an error message while trying to retrieve character information. Steps Taken:
Verified the correctness of the API endpoint URL for character data.
Ensured the user-supplied character ID was valid.
Scrutinized the JSON response from the API to identify any error messages. Outcome: The problem was resolved by rectifying the URL path, directing it to the accurate API endpoint for character data. It was determined that the character ID was being transmitted correctly, but the URL format was at fault.


Problem 2: Enhanced Error Handling Description: 
The application previously exhibited generic error messages that lacked specificity, causing user confusion when issues arose. Actions Taken:
Implemented a robust error-handling mechanism to furnish users with more detailed error messages.
Crafted custom error messages tailored to various scenarios, including invalid inputs, network disruptions, and API-related problems. Outcome: As a result of these measures, users now receive informative error messages that enable them to better comprehend and resolve issues as they arise.


Challenge 3: Strengthening User Input Validation Description: 
Users had the ability to input invalid character IDs, leading to unforeseen system behavior. Actions Taken:
Enhanced user input validation to mandate positive integer character IDs.
Furnished explicit instructions to guide users toward valid input. Outcome: The application has been fortified to validate user input, effectively averting the processing of invalid character IDs.


Instructions for Utilization To make use of this application, adhere to these guidelines:
Duplicate the repository onto your local device.
Unfold the project within Visual Studio.
Construct and initiate the application.
Pursue the on-screen menu prompts to designate preferences for accessing character, episode, or location details.


Credits
Caleb Blevins
