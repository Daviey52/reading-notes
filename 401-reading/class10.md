# Class Ten

[Home](https://daviey52.github.io/reading-notes/)

A stack is a data structure that is made of nodes that reference to the next but not the previous.

Some of the common terminologies for a stack include
. Push – Node put into a stack are pushed
. Pop – Node that are removed from a stack are popped
   Top – is the top of the stack
. Peek – whenever you peek you will see the value of the top    Node in the stack
. isEmpty – return true when the stack is empty otherwise to returns false.

Stack follow the following concepts

First in Last Out (FILO)
This means that the first item added in the stack will be the
last item popped out of the stack

Last in first Out (LIFO)
This means the last item added to the stack will be the first item popped out of the stack.

Pushing a node into a stack will always be an 0(1) operation. This is because it takes the same amount of time no matter how many Nodes you have. When adding a Node, you push it into the stack by assigning it the new top, with its next property equal to the original top.

You typically check isEmpty before conducting a pop. This ensures that an exception is not raised. Alternatively, you can wrap the call in a try/catch block.

When conducting a peek, you are only inspecting the top Node of the stack.

Common terminology for a queue
• Enqueue – Node or item that are added to the queue.
• Dequeue – Node or items that are removed from the queue
• Front – this is the first Node of the queue
• Rear – this is the last Node of the queue
• Peek – when you peek you will see the fron Node
• IseMPTY – RETURN TRUE WHEN THE QUEUE IS EMPTY OTHERWISE IT IS FALSE

First In first Out (FIFO)
This means that the first item in the queue will be the first item out of the queue.

Last In Last Out (LILO)

This means that the last item in the queue will be the last item out of the queue.

Enqueue 0(1) – when adding an item to a queue, it has a constant big 0

Dequeue 0(1)  - when removing an item from a queue , it has a constant big 0
