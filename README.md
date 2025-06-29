# CS-320
Building software that works correctly is important. To do this, it helps to test the software carefully while it is being built. Testing each small part of the program makes sure everything works as it should. In my project, I worked on three parts: contacts, tasks, and appointments. I wrote tests that matched the rules each part had to follow.

For the contact part, I tested that every contact had a unique ID that could not be changed. I also checked that names and phone numbers were not too long. If someone tried to add a contact with the same ID twice, the test made sure the program showed an error.

For the task part, I tested that task IDs, names, and descriptions followed rules about length and could not be empty. I checked creating, reading, updating, and deleting tasks to make sure they worked properly. I also tested what happened if someone asked for a task that did not exist.

The appointment part was trickier because it involved dates. I tested that appointment IDs were unique and that the dates were always in the future. I made sure the program would not allow dates in the past. Since dates can be changed by mistake, I made copies of date objects to protect the original dates from being changed outside the program.

The tests covered many situations. I checked normal cases, border cases like the longest allowed names, and wrong cases like bad IDs or past dates. I used test methods that checked if errors were thrown when they should be, and if the program behaved correctly otherwise.

Writing these tests helped me find mistakes early and gave me confidence the program worked well. I also took care to write tests that tried to break the program to catch hidden bugs. For example, I tested invalid inputs and tried to cause errors on purpose.

Using methods to set up common data before each test helped me avoid repeating the same code and made the tests faster and easier to read.

In the future, it would be good to add tests that check how the parts work together and how the whole program runs as one. Performance tests would help see how the program behaves when many users use it at the same time.

Finally, I learned that testing your own code can be tricky because you might expect it to work. To avoid this, I focused on testing things that could go wrong, which made the software better and more reliable.

By writing thorough tests and following good programming habits, I am helping to make sure the software will stay reliable, easy to fix, and safe to use over time.

