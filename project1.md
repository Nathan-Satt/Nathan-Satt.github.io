[Back to Portfolio](./)

File Transfer Client
===============

-   **CSCI 332:** 
-   **100:**
-   **C++:**
-   **Source Code Repository:** [File Transfer Client](https://github.com/Nathan-Satt/FileTransfer/)  
    (Please [email me](mailto:NDSatterfield@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This program allows a user to send a text file over the network to a remote server running the accompaning server side code. The program asks the user for a port number IP address and file name and it then begins to send the file. It does this by finding the length of the file which it then sends to the server so the server will know when the transfer is complete. It then begins reading in the file 999 bits at a time and then sending that chunk as a single packet this is done untill there is no more data left to send.

## How to compiles / run the program

How to compile (if applicable) and run the project.

```bash
g++ Client_task2.cpp -g -lpthread -lrt -o Client_task2.out
./Client_task2.out
```

## UI Design

Lorem ipsum dolor sit amet (see Fig 1), consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat (see Fig 2). Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum (see Fig 3).

![screenshot](images/Client.png)
Fig 1. Client input prompts 

![screenshot](images/ServerSide.png)
Fig 2. Server Side output

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
