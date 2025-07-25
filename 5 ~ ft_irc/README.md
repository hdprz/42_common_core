# ft_IRC

>[!NOTE]
> Group project done with [@hhecquet](https://github.com/hhecquet) | [@bepoisso](https://github.com/bepoisso/)


The ***ft_IRC*** project is a 42 networking assignment where we created an Internet Relay Chat (IRC) server from scratch in C++. The goal was to implement a server that could handle multiple client connections, manage channels, and support basic IRC commands while following the RFC 2812 protocol specifications.
This project deepened our understanding of socket programming, concurrent client handling, and network protocol implementation.

What we had to do:
* Implement core IRC server functionality:
  * Client connection and authentication
  * Channel creation and management
  * Private messaging between users
  * Basic command parsing and execution
  * User roles and privileges (operators)
* Handle multiple simultaneous connections using poll()
* Process and relay messages between clients
* Maintain consistent server state across operations
* Implement error handling and edge cases

Core Features Implemented:
* User Management
  * NICK - Change nickname
  * USER - Set username and realname
  * QUIT - Disconnect from server
* Channel Operations
  * JOIN - Join or create channels
  * PART - Leave channels
  * KICK - Remove users from channels
  * MODE - Modify channel/user modes
  * TOPIC - Set/view channel topics
* Communication
  * PRIVMSG - Send messages to users/channels
  * NOTICE - Send notices
  * WHO - Query user information
  * LIST - List available channels

What We Learned:
* Deep understanding of **TCP/IP networking**
* Socket programming and connection management
* Protocol implementations
* Robust error handling in networked applications
* C++ design patterns for server architecture

FT_IRC was a challenging project that taught us the intricacies of network programming and protocol implementation. The bonus features added practical utility while deepening our understanding of client-server architectures.