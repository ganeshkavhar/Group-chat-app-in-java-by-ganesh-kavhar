# Group-chat-app-in-java-by-ganesh-kavhar
ganesh kavhar java apps development

Save the file as GroupChat.java and compile it using javac and then run the program using two command line arguments as specified. A multicast host is specified by a class D IP address and by a standard UDP port number. Class D IP addresses are in the range 224.0.0.0 to 239.255.255.255, inclusive. The address 224.0.0.0 is reserved and should not be used.
Here is a sample output of the above program:
multicast socket api in java

multicast socket api in java1multicast socket api in java12
We have used the multicast host IP address as 239.0.0.0 and the port number as 1234 (since the port numbers 0 through 1023 are reserved). There are 3 members in the group: Ironman, CaptainAmerica, and Groot. Start all three terminals first before sending the message, otherwise messages which are sent before starting the terminal are lost (since there is no facility of buffer incorporated to store the messages.) We need two threads in this application. One for accepting the user input (using the java.util.Scanner class) and the other for reading the messages sent from other clients. Hence I have separated the thread which does the reading work into ReadThreadclass. For leaving the group, any of the user can type in Exit to terminate the session.

The above program is executed on a single machine. Socket programming is meant for distributed programming. The same piece of code snippet when present on different machines which have Java installed can satisfy that requirement. This is just the bare bones service logic. The project would be even more fascinating if the front-end is developed. You can use Java’s AWT (Abstract Window Toolkit) or its advanced counterpart, Java Swing to develop the front end. Since this wouldn’t be part of Socket programming I’m leaving it untouched without getting into the details.
Additional points:

You can incorporate network security feature by performing encryption before sending the message over the network.
Primitive techniques such as Caesar cipher or advanced methods such as RSA can be used to perform encryption-decryption. You can try using Java’s RMI (Remote Method Invocation) to perform the same task.
Here, you can leverage the abstraction offered by Java to maximum extent. However, if your primary objective is efficiency, then Socket programming is the best choice. Since it doesn’t require any run time support, it is a bit faster compared to RMI.
