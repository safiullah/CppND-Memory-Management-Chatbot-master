# CppND-Memory-Management-Chatbot-master
 This is my Udacity C++ Project For Memory Management Course. The Student code is downloaded from the following repository, where the complete details and all dependencies can be found.
 
 https://github.com/udacity/CppND-Memory-Management-Chatbot.git
 
 # Task 0 Debug Warm-Up Task
 The Code crashes when closing the window and it must be debugged to stop the code from crashing.
 Completed with commit 6962197.
 
 # Task 1 : Exclusive Ownership 1
In file chatgui.h / chatgui.cpp, make _chatLogic an exclusive resource to class ChatbotPanelDialog using an appropriate smart pointer. Where required, make changes to the code such that data structures and function parameters reflect the new structure. 

# Task 2: The Rule of Five
Class design meets the Rule of Five guidelines.
In file chatbot.h / chatbot.cpp, changes are made to the class ChatBot such that it complies with the Rule of Five. Memory resources are properly allocated / deallocated on the heap and member data is copied where it makes sense. In each of the methods (e.g. the copy constructor), a string of the type "ChatBot Copy Constructor" is printed to the console so that it is possible to see which method is called in later examples.

# Task 3 : Exclusive Ownership 2
In file chatlogic.h / chatlogic.cpp, adapt the vector _nodes in a way that the instances of GraphNodes to which the vector elements refer are exclusively owned by the class ChatLogic. Use an appropriate type of smart pointer to achieve this. Where required, make changes to the code such that data structures and function parameters reflect the changes. When passing the GraphNode instances to functions, make sure to not transfer ownership and try to contain the changes to class ChatLogic where possible. 

