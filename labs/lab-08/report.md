## Checkpoint 1
![image](https://user-images.githubusercontent.com/46334090/179251510-422ca226-fa47-4acd-a25b-92ab3c9b68b6.png)
## Checkpoint 2
### Question 2
1. In order to see what tests were run, click on a build and then scroll all the way down on the subsequent page. Then, click on "View Tests Summary" and you'll get to a page where you can see the tests run. For example: https://open.cdash.org/viewTest.php?buildid=8041098
2. You can click on the failed test and check out what the actual stderr message was (for example: https://open.cdash.org/test/756265342). In this case, the error seems to be that "Policy CMP0111 is not set", which is useful for developers as they can use this error message to know what to target when debugging. In this case, it will probably have something to do with Policy CMP0111.
3. The dashboard seems pretty clean, and there are not any errors that I feel that I need to be concerned with.
### Question 3
There are no errors that are inconsistent with other projects using my architecture.
### Question 4
![image](https://user-images.githubusercontent.com/46334090/179259426-6669ba96-9a63-4a52-972d-46becc168d4b.png)
## Checkpoint 3
### Question 3
The failure shows that we have an issue with the copyright. `-VV` gives more detailed output regarding each individual test.
### Question 4
![image](https://user-images.githubusercontent.com/46334090/179261998-2ab98a8b-f862-4eb4-85dd-f098f154258f.png)
### Question 5
Ran `git restore Copyright.txt` in the cmake directory. Now the output after running `ctest -I 11,26 -VV` is:
![image](https://user-images.githubusercontent.com/46334090/179262494-3d15ad0c-8dcd-4997-9ba6-9dee60defa33.png)
## Checkpoint 4
https://github.com/charlestian23/lab8checkpoint4
![image](https://user-images.githubusercontent.com/46334090/179612558-6b67708e-7079-44f6-a019-b362baa5cf9a.png)
![image](https://user-images.githubusercontent.com/46334090/179612615-8987a3c6-d3c5-4ae1-93e3-3e3290cd7308.png)
