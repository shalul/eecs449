EECS 449 Warm-Up Assignment 

Part 1:

Swagger:
<img width="1104" alt="Screenshot 2024-09-27 at 5 02 19 PM" src="https://github.com/user-attachments/assets/7f828477-9e94-408a-8272-167ec491acc6">

Walker responses:
<img width="1074" alt="Screenshot 2024-09-27 at 6 09 23 PM" src="https://github.com/user-attachments/assets/8cc2c989-80a8-4629-9768-246b337e278f">
<img width="1030" alt="Screenshot 2024-09-28 at 4 54 44 PM" src="https://github.com/user-attachments/assets/cab75de9-5397-4938-81af-6ae3031f4662">

Part 2:

using gemma2:
<img width="605" alt="Screenshot 2024-09-28 at 5 20 29 PM" src="https://github.com/user-attachments/assets/34c3c95d-3907-47e0-83de-ce33b1b0a02c">


using llama3.1:
<img width="630" alt="Screenshot 2024-09-28 at 1 09 25 PM" src="https://github.com/user-attachments/assets/8eb23648-5285-4777-ad32-6307704239b5">

Part 3:

I've made a ChatType that greets users when they prompt something. The chatbot is required to ask the user about how their day is going.

The chatbot will take the user input. The items in the enum for ChatType are flagged based on the context of the prompt given, so for GreetingsChat, it will be flagged for "handling greeting/welcome messages". The chatbot will identify this and then reroute to the GreetingChat model.

Output:
<img width="630" alt="Screenshot 2024-09-28 at 1 09 25 PM" src="https://github.com/user-attachments/assets/918e32c9-b183-4e38-8739-d938dc339eea">

