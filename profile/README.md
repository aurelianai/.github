# Aurelian AI
Aurelian aims to bring first class support to self hosted LLMs with two projects.
1. [Aurelian-Desktop](https://github.com/aurelianai/Aurelian-Desktop)
2. [Aurelian-Server](https://github.com/aurelianai/Aurelian-Server)

# Why does this Organization Exist
Software has made our lives far less private.
 - Search
    - There will be a record of the query, or at least you couldn't guarantee there would not be as that data is out of your hands.
 - E-Commerce
    - Similar to search, the order data and address are out of the user's hands
 - Food Service
    - In order for food to be served, an order and an address for delivery must be shared.

LLM inference seems like it should belong here, but it doesn't. Privacy is lost becuase inference requests must be exposed in plaintext to LLM recieving it. However, (unlike search) this server can be under end-user control offering inference without the exposure of **ANY** data. Aurelian targets two use cases.

1. [Aurelian-Server](https://github.com/aurelianai/Aurelian-Server): Organizational use where a shared GPU server powers inference and chats are stored in an external database.
2. [Aurelian-Desktop](https://github.com/aurelianai/Aurelian-Desktop): Personal use where inference and chat persistence are done on the end-user.

# State of the Project
This is a solo project for now, so neither repo is in working condition. [Aurelian-Server](https://github.com/aurelianai/Aurelian-Server) will be released first since it's closer to completion. There is a demo running at [demo.aurelianai.com](demo.aurelianai.com) anyone can use. Feel free to check it out!
