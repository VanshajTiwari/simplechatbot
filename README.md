# CDP Chatbot

## Objective:
The goal of this project is to develop a chatbot capable of answering "how-to" questions related to four major Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap. The chatbot will retrieve relevant information from the official documentation of each platform to help users perform tasks or achieve specific outcomes within the respective platforms.

## Data Sources:
- **Segment Documentation**: [Segment Docs](https://segment.com/docs/?ref=nav)
- **mParticle Documentation**: [mParticle Docs](https://docs.mparticle.com/)
- **Lytics Documentation**: [Lytics Docs](https://docs.lytics.com/)
- **Zeotap Documentation**: [Zeotap Docs](https://docs.zeotap.com/home/en-us/)

## Core Functionalities:
1. **Answer "How-to" Questions**:
   - The chatbot should understand and respond to user queries about how to perform specific tasks or use features within each CDP.
   - Example questions:
     - "How do I set up a new source in Segment?"
     - "How can I create a user profile in mParticle?"
     - "How do I build an audience segment in Lytics?"
     - "How can I integrate my data with Zeotap?"

2. **Extract Information from Documentation**:
   - The chatbot should retrieve relevant information from the documentation to answer user queries.
   - It should navigate through the documentation, identify sections, and extract the necessary instructions or steps.

3. **Handle Variations in Questions**:
   - The chatbot should handle different variations in question length, phrasing, and irrelevant topics.
   - Example: If a user asks something unrelated like "Which movie is getting released this week?", the chatbot should inform them that it's beyond the scope of the platform.

## Bonus Features:
1. **Cross-CDP Comparisons**:
   - The chatbot can answer questions comparing the functionalities of the four CDPs.
   - Example question: "How does Segment's audience creation process compare to Lytics'?"

2. **Advanced "How-to" Questions**:
   - The chatbot can handle complex platform-specific queries and provide guidance on advanced configurations, integrations, or use cases.

## Implementation Details:
- **Kommunicate**: Used to create a custom chatbot.
- **Integration**: The chatbot is integrated into an HTML webpage, where it can be accessed and interacted with directly.

## Setup Instructions:

1. **Set Up Kommunicate Bot**:
   - Follow [Kommunicate's integration documentation](https://docs.kommunicate.io/docs) to create and configure the custom bot.
   - Integrate the bot with your HTML page by adding the provided bot script in the `head` section of your HTML.

2. **Customize Chatbot**:
   - Modify the chatbot responses based on the CDP documentation.
   - Use the provided API to extract documentation content or set up a document indexer (e.g., Elasticsearch) to facilitate searches.

3. **Deploy the Web Application**:
   - Once your bot is integrated, deploy the HTML application using platforms like **Netlify**, **Vercel**, or **GitHub Pages**.

## Example Usage:
- Users can ask the chatbot about any "how-to" tasks related to Segment, mParticle, Lytics, or Zeotap. The chatbot will search the documentation and provide step-by-step instructions.
- The bot can also compare functionalities between the CDPs or answer more advanced configuration questions.

## Contribution:
Feel free to fork this repository, make improvements, and submit pull requests. Contributions are always welcome!

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
