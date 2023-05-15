# Inject 2.0 AI ChatBot by Joseph Straight
## Manual QA Testing of the ChatBot

### Test Scenarios and Cases

#### Test Scenario 1: Verify the chatbot's ability to understand complex multi-turn conversations/ questions related to Inject 2.0.

##### Test Case 1.1:
- **Input 1:** "How do I create a new template in the application?"
  - **Expected Output 1:** The chatbot provides a step-by-step guide to create a new template.
  - **Actual Output 1:** To create a new template in Inject, you can use the web interface and create a template with just a few clicks. Once you have created the template, it can be customized with some special commands...

- **Input 2:** "Can I add new effects that are available from the store of the application?"
  - **Expected Output 2:** The chatbot explains how to add a new effects from the available effects in the Inject Store such as the Hotel Key Effect or the Houdini’s Eyes effect, maintaining the context from the previous input.
  - **Actual Output 2:** Yes, you can add new effects that are available from the store of the Inject application...

##### Test Case 1.2:
- **Input 1:** "What if I change to a new phone and all of my custom effects are gone?"
  - **Expected Output 1:** The chatbot provides instructions on how to recover the already existing profile of an Inject customer.
  - **Actual Output 1:** If you change to a new phone, you don't have to worry about losing your custom effects...

- **Input 2:** "But what if I also don't have access to my recovery email?"
  - **Expected Output 2:** The chatbot suggests alternative ways of account recovery or contacts support, maintaining context from the previous conversation.
  - **Actual Output 2:** Hmm, I am not sure...

#### Test Scenario 2: Evaluate the chatbot's ability to handle queries related to the Inject 2.0 Manual.

##### Test Case 2.1:
- **Input 1:** "How do I enable the Vibration Feedback?"
  - **Expected Output 1:** The chat should reply with the exact step-by step instructions on how to enable the vibrational feedback.
  - **Actual Output 1:** To enable the Vibration Feedback option in Inject, you need to go to the Application Settings Tab and turn on the Vibration Feedback toggle...

- **Input 2:** “How can I transmit a playing card to the spectator’s phone?”
  - **Expected Output 2:** The chatbot should give the user a step by step guide on how the transmissions of information are happening from the magician’s device to the spectator’s device.
  - **Actual Output 2:** To transmit a playing card to the spectator's phone using Inject, you need to follow these steps...

- **Input 3:** “What is the covert typing feature and how to use it?”
  - **Expected Output 3:** The chatbot should explain in detail what is the covert typing feature and how to use it plus how to edit/change/add the secret covert typing text.
  - **Actual Output 3:** The Covert Typing feature in Inject allows you to secretly transmit a message to another device...

#### Test Scenario 3: Test the chatbot's response to different user sentiments.

##### Test Case 3.1:
- **Input:** "I am really frustrated. Your app is too complicated."
  - **Expected Output:** The chatbot empathizes with the user ("I'm really sorry to hear that you're feeling this way...") and offers help or guidance to simplify the user's experience.
  - **Actual Output:** I'm sorry to hear that you're feeling frustrated with Inject...

#### Test Scenario 4: Test the chatbot's ability to handle interruptions in a conversation flow.

##### Test Case 4.1:
- **Input 1:** "Can you tell me how to host my images for the effect that I would like to create?"
- **Input 2:** (before the chatbot responds to Input 1) "Actually, never mind. Can you tell me the exact link to my Fake Google Page?"
  - **Expected Output 2:** The chatbot smoothly transitions to providing steps on how to delete an account.
  - **Actual Output 2:** Certainly! To host your images for the effect that you would like to create...

#### Test Scenario 5: Test the chatbot's fallback strategy when it fails to understand user input.

##### Test Case 5.1:
- **Input:** "How can I flibberjabber the doodah?"
  - **Expected Output:** The chatbot politely indicates confusion and asks the user to rephrase or provide more information.
  - **Actual Output:** Hmm, I am not sure...

### Conclusion

In conclusion, the Inject 2.0 AI ChatBot serves its main purpose effectively - answering user queries related to the Inject 2.0 application and its manual. The ChatBot demonstrates a solid understanding of the application and is generally successful in providing accurate and relevant responses to inquiries. It handles complex multi-turn conversations and offers comprehensive information about the application's features. It also responds appropriately to different user sentiments, demonstrating an empathetic approach to user frustrations and inquiries.

However, the testing has uncovered a few areas that require attention. The ChatBot occasionally fails to provide complete information, missing out on explaining some features in depth, such as the "qp qm" feature and the time delay option of the covert typing in Inject. In addition, the ChatBot struggles to handle interruptions in a conversation flow, which could be improved by incorporating a mechanism for stopping the generation of a response when an interruption occurs.

The fallback strategy of the ChatBot when it fails to understand user input is appropriately polite and prompts the user to provide more details or rephrase their question. This is a positive indication of the ChatBot's ability to handle unexpected or unclear inputs.

Based on the findings of this report, I recommend prioritizing the enhancement of the ChatBot's comprehension of the application's features and its ability to handle conversation interruptions. Addressing these issues will significantly improve the user experience and performance of the Inject 2.0 AI ChatBot.

In light of the test results, the ChatBot is deemed ready for use with the understanding that improvements will continue to be made in the areas highlighted in this report.



The complete Test Cases and comments from the Quality Assurance Engineer can be found [HERE](https://docs.google.com/document/d/1DBiTsUXrXVFhM6eL8a6jUAQXW1FlwmLx9_k02_2YZFI/edit?usp=sharing)

