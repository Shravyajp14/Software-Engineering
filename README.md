# Software-Engineering Minor Project
# ASSIGNMENT 1
### Problem Statement:
Write a C program to show that the C programming language supports Call by Value only.

### Business scenario:
AssetZen, a financial firm, provides an investment risk assessment tool for clients to evaluate their portfolio performance. It needs to develop a reliable investment risk assessment tool that
allows financial analysts to calculate the squared values of investment returns while ensuring that the original client data remains unchanged to maintain data integrity and support informed decision-making..

### Business Use Case:
In portfolio management, evaluating the volatility of investment returns is a critical aspect of assessing risk. Squaring the returns amplifies the impact of both large gains and large losses,
making it easier to detect volatility. AssetZen’s tool will empower financial analysts to

1)Calculate squared returns for different assets in the client’s portfolio.

2)Preserve original data, ensuring that no modification occurs to the client’s historical data, which could lead to faulty assessments.

3)Provide risk insights to clients based on these calculations to guide investment strategies.

Example of Squared Returns:
To illustrate the calculation, consider an investment with a return of 5%. The squared value would be:
(0.05)*(0.05)=0.0025
For a negative return of -5%, the squared value would be:
(-0.05)*(-0.05)=0.0025
By squaring both positive and negative returns, the tool helps analysts give more weight to extreme values and make accurate risk assessments.

# ASSIGNMENT 2
### Problem Statement:
Study the concept “USABILITY”. Prepare a report on USABILITY of atleast TWO UIs of major software product you have seen.
Usability is the most important factors that affects the user experience of any application, website, or any other piece of software.

Two popular software interfaces: Amazon and Adobe photoshop.
##### Amazon(Website and Mobile App):
Amazon is one of the world’s largest e-commerce platforms, allowing users to purchase a wide range of products,from electronics to groceries. Its interface is designed to facilitate easy browsing, product discovery, and smooth transactions.
• Efficiency: Amazon is highly efficient with features like one-click checkout, saved payment info, and personalized recommendations, making shopping faster and more convenient. Its robust search
function allows users to filter by criteria such as price and reviews, further streamlining product discovery and purchases.

• Learnability: Amazon's interface is easy for new users to navigate, with a clear search box, categories, and labels guiding them through the shopping process, while the mobile app offers similar functionality
with mobile-friendly adjustments.

• Memorability: Amazon's consistent design and intuitive layout, search filters, and account management, make it easy for users to remember how to navigate the platform even after a long period of non-use.

• Error Prevention and Recovery: Prevention and Recovery: Amazon provides clear feedback when errors occur, such as invalid credit card information or unavailable products. It guides users through solutions,
such as choosing alternative delivery options or payment methods.

• Satisfaction: Users are generally satisfied with Amazon's user experience due to its fast checkout, personalized recommendations, and helpful reviews, although some find the cluttered homepage and
overwhelming volume of information and ads to be a drawback.

##### Microsoft Teams:
Microsoft Teams is a collaboration platform that integrates chat, video conferencing, file sharing, and app integration to facilitate teamwork. It's widely used in professional settings for remote work and
communicationEfficiency: Word is fast with shortcuts and menus, but finding advanced features can take extra time.
• Efficiency: Microsoft Teams is efficient for team communication with features like persistent chat rooms, channels, and seamless integration with Office tools for document collaboration, though occasional
performance issues like slow loading times can hinder efficiency.

• Learnability: Teams offers a clean and organized interface, but the learning curve can be steep for new users, particularly those unfamiliar with some advanced features, like setting up channels and using third-
party integration. Microsoft offers onboarding tutorials and tips for beginners.

• Memorability: The interface is generally memorable for users who regularly use collaboration tools, as Teams follows a familiar layout: a side panel with options for chats, teams, calendar, and calls.

• Error Prevention and Recovery: Microsoft Teams minimizes the risk of errors through confirmation prompts for critical actions, an autosave feature for files, easy access to chat history for information recovery, and the ability to undo certain actions like message deletions.

• Satisfaction: Microsoft Teams enhances user satisfaction through customizable notification settings for prioritizing conversations, a responsive design that ensures a consistent experience across devices,
seamless integration with other Microsoft 365 and third-party apps, and engagement features like reactions, emojis, and GIFs that add a social element to communication.

 ### Problem Statement:
List all features of programming language and write PROGRAMS to show how they help to write ROBUST code.
##### Theory:
A ROBUST code is a type of programming code that is reliable, can handle errors gracefully, and continues to function correctly under various
conditions without crashing. The features of programming languages are:
• Error Handling:: The ability to detect and respond to errors without crashing the program.

• Type Safety: Prevents operations on incompatible data types, reducing errors during execution.

• Modularity: Proper allocation and release of memory to avoid memory leaks or crashes.

• Memory Management: Ensures that user inputs or external data are valid and safe before processing.

• Input Validation: Ensures that user inputs or external data are valid and safe before processing.


### Problem Statement:
Study the “ASSERTIONS” in C language and its importance in writing RELIABLE CODE. Study POSIX standard and write a C program under
Unix to show use of POSIX standard in writing portable code.

Theory:
• Assertions in C are used to test assumptions made by the programmer during development. They help identify bugs early by ensuring specific conditions (such as variable values or logic) hold true while
the program is running.
• POSIX (Portable Operating System Interface) is a standard that defines a set of system calls, libraries, and guidelines for Unix-based operating systems. Its primary goal is to make applications portable
across different Unix-like systems.
