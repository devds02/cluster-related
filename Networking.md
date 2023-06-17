# Networking related

UDP  
UDP is like sending a postcard.
Imagine you want to send a message to a friend. Instead of putting it in an envelope and ensuring its safe delivery, you write your message on a postcard and drop it in the mailbox.
The postcard doesn't guarantee that it will reach your friend or arrive in order. It may get lost along the way, duplicated, or arrive out of order.
However, sending a postcard is quick and doesn't require the same level of effort and resources as sending a letter in an envelope.
Similarly, UDP sends data packets without establishing a connection or worrying about reliability and order. It's a fast and lightweight method of communication.
UDP is commonly used for situations where speed is more important than reliability, such as real-time communication, video streaming, or gaming.


TCP  
TCP works in a similar way by establishing a connection between two devices before data transfer, ensuring the reliable delivery of information.
It breaks down the data into small packets, sends them in order, and waits for acknowledgments to confirm their successful arrival.
If any packets are lost or damaged, TCP retransmits them to ensure that the data is complete and accurate.
TCP is commonly used for applications like web browsing, email, file transfers, or any scenario where accurate and error-free data transmission is necessary.

