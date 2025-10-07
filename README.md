An introduction to testing applications

In this day in age, almost every device around us runs on some type of software or application. Think about our smartphones, tablets, laptops, smart TV's, cars even our homes. But before any of these devices is released to the main public for everyday use, the device needs to be tested. This also goes for the application running on a particular device.
When talking about application testing techniques, we can distinguish manually testing techniques as well as automated testing techniques. In this blog, I will discuss common manual testing techniques. Furthermore, I will dive a little deeper into Boundary Value Analysis and Decision Table Testing. Finally, I will talk about the future of manual testing with regard to the AI age.

Common manual testing techniques
There are several testing techniques performed manually, which I find to be the most common. These can be divided into manual testing techniques based on the approach of the tester. These can also be based on the purpose of the manually testing technique chosen.

Main division of manually testing techniques
The following is a main division of manually testing techniques.  This approach is determined by the level of knowledge the tester has of the code of the application.

Black Box testing: the approach of the tester for selecting this manually testing technique is that there isn't any knowledge of the internal code of the application which needs to be tested. Functionality of the application is then evaluated by the tester using inputs and outputs. For example: testing the login credentials for memberships of a sport school website. Valid credentials are tested, invalid credentials are tested and "forgot username/e-mail" or "forgot password" are tested.
White box testing: this manually testing technique is chosen by the tester when the tester has knowledge of the code, internal structure and logic of the application which needs to be tested. So, the code, internal workings and logic are evaluated by the tester. For example: testing the discount on membership payments of a sport school. Test if the various discounts are calculated correctly by the internal code. Test the logic of various discounts available to various types of membership. Ensure that the system works properly for all memberships.
Gray box testing: this is a manually testing technique which is a combination of black box and white box testing. The tester has somewhat knowledge of the internal structure, logic and code but still focuses on the perspective of the end user while testing the application.

Subdivision of manually testing techniques
Of the three aforementioned manually testing techniques, a subdivision can be made.
Black box testing technique consists of:
Functional testing: checks if features work as expected.
Non-functional testing: performance, scalability and usability are covered.
Regression testing: verify changes have not influenced existing funtionality

White box testing consists of:
Path examination: making sure all code paths are tested
Output approval: check that code outputs are correct
Security testing: detect weaknesses in the code.
Loop testing: make sure loops function as intended.
Data flow testing: evaluate flow of data through the system.

Gray box testing consists of:
Matrix testing: the relationship between inputs and outputs is reviewed
Regression testing: make sure existing features are not broken by changes
Pattern testing: Based on observed patterns, check for known problems
Orthogonal array testing: different combinations of inputs are systematically tested.

Based on this division, the following manually testing techniques are common.
Functional testing: which includes unit testing, integration testing, system testing, regression testing and user acceptance testing. Functional testing is done to verify if the features of the application work as is expected.
Non-functional testing: includes performance testing, security testing, compatibility testing, usability testing, data conversion. This  testing technique covers features of the application which have nothing to do with the specific functions. With this testing technique, overall performance, reliability and user experience are covered. This means the focus is on aspects like speed, scalability, security and usability which are very important for stability of the system and satisfaction for the end user.
Regression testing: this is done every time new code has been added or has replaced previous code to verify that there are no new bugs and that existing functionality has not been affected. After bug fixes, improvements and updates, regression testing verifies that the application keeps working as expected. This aids maintaining a stable system as the application evolves.

Exploratory testing: this is an informal method which testers use without predefined test cases to explore the software. First they learn about the system and based on their understanding they then test different functionalities. The purpose of this approach is to help finds defects without scripts.
Ad-hoc testing: testers test the application without specific documentation or plans, an evaluation without structure. The purpose of this is to find bugs that may not be identified through structured testing methods. Instead, it relies on the tester's experience and feel. Often this is done spontaneously to identify issues quickly.

Compatibility testing: testing is done to determine whether the application operates correctly across different environments, such as browsers, devices, hardware and operating systems. No matter the platform, the consistency of functionality and performance of the application are checked. The purpose of this testing is to make sure the user has a smooth experience regardless of the configurations.
Sanity testing: this is a quick, focused method carried out after minor changes or bug fixes to validate that a specific functionality works as expected. Critical parts of the software are checked to make sure that there aren't major issues due to changes. This type of testing typically occurs before regression testing for example.

Smoke testing: this technique is performed to test the software's basic functions after a new build or deployment. This is a validation if the system is stable enough to be tested further. If the application failed the smoke test, this means there are major issues that have to be solved in order to continue with detailed testing.

Graphical user interface (GUI) testing: the software's visual and interactive elements are tested to determine that these work as intended. Both functional and non-functional features of the user interface are checked.

Other popular testing techniques
Apart from these common manual testing techniques, there are special techniques for testing certain situations in the application. In this blog, I will address these which are: Boundary Value Analysis and Decision Table Testing (DTT).

Boundary Value Analysis (BVA) is a functional testing technique and thus a black box testing technique. The purpose of BVA is to test numbers at or just beyond the boundaries of a certain range of numbers. The test ensures the application is capable of determining valid and invalid numbers correctly.
For example: if a gym has discounts for its members with a minimum of 5% and a maximum of 10%. The minimum boundary is 5% (correct) with anything less than 5 being invalid, while the maximum boundary is 10% (correct) and anything above invalid. Test cases include the valid range between 5% and 10%. Also test cases with invalid inputs, below 5% and above 10%.

Decision Table Testing (DTT): to define this, let's first look into what a decision table is. It is a tool which is used in testing applications to represent and analyze different combinations of conditions and actions. Decision tables are comprehensively used in testing applications to simplify test scenarios which involve complex decision-making. 

Decision Table Testing is a type of black box testing technique used to organize complex decision logic and to make sure all possible combinations of conditions are tested to achieve a comprehensive test.

The future of manual testing in the age of AI
When talking about AI in software testing, it involves making artificial intelligence and machine learning algorithms an integral part of the software testing process. Advantages include accurate results and time saving. There are lots of AI tools available to help improve manual testing. Four main aspects of software testing are thus modernized:
Preparation of test cases;
Generation of test data;
Bug predictions;
Results analysis.

Though AI can improve manual testing, the human creativity, intuition and feel cannot be replaced.

In conclusion, with regard to the common manually testing techniques, there are lots of techniques available for manually testing applications. This ensures a complete and thorough analysis of the functionality of an application. The same goes for the non-functional part of the test phase of the application.
Furthermore, AI can aid in improving manual testing of applications but the human creativity, intuition and feel are still very important in manually testing applications.

Sources:
https://www.globalapptesting.com/blog/types-of-manual-testing

https://www.browserstack.com/guide/decision-table

https://dev.to/nithyakala_krishnasamy_39/future-of-manual-testing-in-the-age-of-ai-1j93
