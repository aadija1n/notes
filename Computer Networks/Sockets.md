to be added later ...

---

### Practice Questions

> **Q.** A server process has executed socket(), bind(), and listen(). A client process executes socket() and connect(). The server has not yet executed accept(). Which of the following is TRUE? **(Gate 2018)**
> 
> 1. connect() fails.
> 
> 2. connect() succeeds and the connection waits in the backlog queue.
> 
> 3. Server process terminates.
> 
> 4. Client waits forever.
> 
> <br>
> 
> <details>
>     <summary>Click here to reveal answer.</summary>
>     <br>Correct Answer : 2<br>
>     <br>Explanation : After listen(), the OS can complete the TCP handshake and place the connection in the backlog queue even before the server executes accept().
> </details>

> **Q.** In the client-server model, which side calls listen() ?
> 
> <details>
>     <summary>Click here to reveal answer.</summary>
>     <br>Correct Answer : Server
> </details>

> **Q.** Consider the sequence of operations when a browser accesses a webpage for the first time:
> 
> ARP Request → DNS Query → TCP Connection Establishment → HTTP GET
> 
> Which operation corresponds to interaction with an application-layer server ?
> 
> **(GATE 2019)**
> 
> 1. ARP Request.
> 
> 2. DNS Query.
> 
> 3. HTTP GET
> 
> 4. Both (2) and (3)
> 
> <br>
> <details>
>     <summary>Click here to reveal answer</summary>
>     <br>Correct Answer : 4<br>
>     <br>Explanation : Both DNS and HTTP works on application layer
> </details>

> **Q.** Which server-side socket function is responsible for accepting an incoming client connection in the provided C++ example ?
> 
> 1. bind()
> 
> 2. connect()
> 
> 3. accept()
> 
> 4. send()
> 
> <br>
> <details>
>     <summary>Click here to reveal answer</summary>
>     <br>Correct Answer : 3
> </details>


