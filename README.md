# NoOn-Call
Reduce the on-call

## Description
Reduce the on-call. When your boss call you when you are sleep or your team members ask some basic questions, it can help you accept the phone call or whatsApp call. You can upload your daily or knowledge on the local DB and it can answer the question based on the information you have put on the DB.

## Function

- Design a DB for unstructure Data
- Build the Local DB
- Time Stamp Set
- App connect and control the response
- voice system to simulate owner's voice
- GPT analysis
- design a  custom moddle level tools to make sure the ai will only response specific person specific answer with target questions.

## Dependency

### Tools
A tool for GPT to access the neo4j and it can help it to access the audio and make sure all the input is controlled.

Here is the flow:

colleges call -> input(audio / txt / image) -> toolsA (handle it and parse it into xml format) -> GPT -> toolsB (do the search in neo4j and use the results generate the response and new code to show the graph information) -> call predefined AGENT -> generate the response to others.

### MacOS
- neo4j-community-5.19.0-unix
## Contributors
Fuhao Ruan
