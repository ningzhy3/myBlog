+++
author = "Hugo Authors"
title = "Process communication"
date = "2021-01-31"
description = "Lorem Ipsum Dolor Si Amet"
tags = [
    "Operating system",
    "Computer science",
     "thumbnail",
]
thumbnail= "images/jincheng.webp"
+++



# Process communication

## 1. Interprocess Communication

A process is independent if it cannot affect or to be affected by the other process. If two or more processes are dependent on each other which need communication, we say interprocess communication. There are two fundamental models of interprocess communication: **shared memory** and **mes- sage passing**.



a. Shared memory

A part of memory is shared by cooperating processes. Processes can exchange information by reading and writing data to the shared memory to communicate.



b. Message passing

In message passing model, communication takes place by means of messages exchanged between the cooperating processes.

send(A, message)—Send a message to mailbox A.
receive(A, message)—Receive a message from mailbox A.

