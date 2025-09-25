# The OSI Model
A 7-layer framework that explains how data travels between computers on a network (a group of two or more connected devices that can communicate and share data, resources, or services with each other over wired or wireless links), from raw electrical signals up to the programmes you use.
A cool nmemonic to remember the order: 
A Priest Saw Ten Nuns Doing Push-ups
* Application Layer (Where user programmes interact with the network [web browsers, email clients, e.g., Gmail, Outlook, etc..])
* Presentation Layer (Makes data usable by translating, encrypting, or compressing it).
* Session Layer (Manages starting, keeping, and ending conversations between devices).
* Transport Layer (Ensures data is delivered reliably and in order (TCP, UDP).
* Network Layer (Decides the path that packets take across networks using logical addresses [IP] and routing).
* Data-link Layer (Handles node-to-node delivery on the same network and physical addressing [MAC]).
* Physical Layer (The cables, signals, radio waves, and electrical details that carry raw bits between devices).

### Why the OSI Model Matters:
* It provides a common language for designers and troubleshooters to isolate problems to a specific layer.
* It lets engineers develop or replace technologies in one layer without reworking the whole stack.
* It is a useful teaching and diagnostic tool.
* Using layers to classify functions and threats helps teams design defenses (like encrypting at presentation or transport layers, filtering at network or data-link layers) and aligning security controls with specific attack surfaces.
* A single, layered reference makes it possible for different vendors and protocols to work together by defining clear roles for each part of communcation, so hardware and software from different suppliers can interoperate.

### Helpful analogy
Think of sending a letter:
Application is writing the message;
Presentation is translating or encrypting it;
Session is arranging the delivery window;
Transport is splitting a long message into numbered pages and ensuring all arrive;
Network is choosing the roads;
Data Link is getting the letter from one post office to the next;
Physical is the truck, plane, or road that moves the package.
