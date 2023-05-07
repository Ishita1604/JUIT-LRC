# 📚 JUIT Library Simulation
Python-based Discrete Event Simulation of my College's Library using SimPy package.
This allows users to simulate how a library operates by borrowing and returning books.

## 📍 Getting Started
To use this library management system, we need to have Python 3 and the following packages installed:
```
simpy
pyyaml
colorama
```
https://simpy.readthedocs.io/en/latest/simpy_intro/installation.html

## 🔍 Scenario
- The library contains books that have a limited quantity available for students to request. Students who are registered with the library can request to borrow a book by visiting the library. If the requested book is available, the student can borrow it immediately. However, if the book is currently unavailable, the student must either wait in a demand queue or wait for another student to return the book.

- Alternatively, students with a special gold membership have the privilege of borrowing books without having to wait in the queue.

## 🚀 Features
- Displays current time: The system displays the current time so that users can keep track of the time while using the library system.
- Displays closing time of the library: The system displays the closing time of the library so that users can plan their visit accordingly.
- Shows how much time is left: The system shows how much time is left until the library closes, giving users an idea of how much time they have left to borrow or return books.
- Displays entire book list of the library: The system displays the entire book list of the library so that users can browse and search for books.
- Displays quantity of each item: The system also displays the quantity of each item in the library, allowing users to know the availability of a particular book.
- Real-time simulation of students arriving at the library: The system simulates the arrival of students in real-time, giving users an idea of the traffic in the library.
- Provision for requesting books: The system provides a provision for requesting books, allowing users to request books that are not available in the library.
- Students can borrow books: The system allows registered students to borrow books from the library.
Provision to return books: The system also allows students to return books that they have borrowed from the library.
- All information is recorded and displayed: The system records all the information related to borrowing, returning, and requesting books, and displays it to the user.
- All information is stored in a separate text file: All the recorded information is stored in a separate text file, allowing users to access and analyze it later.

## 📌 Output Snippet

![Simulation Output](https://github.com/Ishita1604/JUIT-LRC/blob/main/LRC-Output.png)
![Simulation Video](LRC-Video.mp4)

## 📢 Contributors
- [Ishita1604](https://github.com/Ishita1604)
- [nandini-2407](https://github.com/nandini-2407)
