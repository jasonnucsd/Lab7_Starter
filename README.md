Jason Naidu

## Check Your Understanding
1) Where would you fit your automated tests in your Recipe project development pipeline Select one of the following and explain why.

Within a Github action that runs whenever code is pushed 
This ensures that all code is automatically checked before being merged. Manually running tests defeats the purpose and security of automation, and running them after development is complete is too long without testing.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
No. This is not necessarily a user-originated action, and doesn't necessitate the use of an entire E2E test. A function output can be tested in much easier ways, such as the console or a unit test.

3) What is the difference between navigation and snapshot mode?
Navigation mode analyzes a page when it loads, whereas snapshot mode analyzes a page in a given stat3e for accessibility issues.

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
1. Images could be properly sized to reduce the size of transmitted data.
2. The largest image could be preloaded to reduce load time.
3. WebP and AVIF could be used as image formats to allow better image compression.