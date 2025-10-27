Welcome to the **Thunderbird for iOS** client roadmap!

# 🏗️ Active
* **Initial Receive Mail (JMAP)** - Formalize the protocol layer/interfaces and implement the JMAP protocol enough that it will allow us to ingest information from a real email server.
* **Send Mail (JMAP)** - Implement the JMAP protocol enough that it will allow us to send a message from a real email server.

# 📋 Planned
* **Initial Message Database** - Create the initial message store database.
* **Initial Message List** - Create a rudimentary message list implementation that is able to show one folder.
* **Initial Account Setup** - Add support for the initial account setup flow to allow users to set up the required details to access an email server.

# 🚀 Launched
* **Architecture** - Establish a robust and scalable architecture to begin the Thunderbird for iOS project and create the backend. This architecture will include strategies for code sharing across platforms, taking into account the Android and Desktop clients.
* **Autoconfiguration: Add DNS MX lookup to autoconfig feature library**
* **Autoconfiguration: Move SRV record lookup into autoconfig feature library and delete Autodiscover core library**

# 🗃️ Backlog
* **Encrypted Email** - Design a method of encrypting email, considering different encryption mechanisms and security levels.
