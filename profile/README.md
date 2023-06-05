# Aurelian AI
Aurelian aims to bring first class support to self hosted LLMs through a great UI, Aurelian Desktop. <br>
This github organization houses the following repositories: 
- <a href="https://github.com/aurelianai/Aurelian-Desktop">Aurelian Desktop</a> 
- <a href="aurelianai.dev">aurelianai.dev</a> (<a href="https://github.com/aurelianai/Aurelian-Desktop">repo</a>): Docs for Aurelian Desktop, hosted on Github Pages

# Why does this Organization Exist
Software has made our lives far less private. In certain cases, this can't be avoided completely. 
 - Search
    - There will be a record of the query, or at least you couldn't guarantee there would not be as that data is out of your hands.
 - E-Commerce
    - Similar to search, the order data and address are out of the user's hands
 - Food Service
    - In order for food to be served, an order and an address for delivery must be shared.

LLM inference seems like it should belong here, but it doesn't. Privacy is lost becuase inference requests must be exposed in plaintext to LLM recieving it. However, (unlike search) this server can be under end-user control offering inference without the exposure of **ANY** data. For enterprise, GPU racks can be purchased for less than 6 figures. For a personal use case, a server can be run on the same machine as Aurelian Desktop using a smaller model. 

Aurelian Desktop is a universal front end that
1. Is usable by non technical people
2. Consumes a simple and standardized API
3. Supports inference over knowledge