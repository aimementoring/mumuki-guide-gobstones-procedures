Well, we already know how to create procedures, but why would we want to create them?
Some possible answers:

- in order to **simplify code**, writing things we will do many times, only once and in only one place;
- in order to **write less**, since us programmers are a little lazy;
- in order for the purpose of our program to be **more comprehensive to humans beings**, as we saw in the example of `DrawBlackSquareSide3`. For this, it is essential to think good names, but neither too long (`DrawABlackSquareOfWidth3AndOfLarge3`), nor too short (`DraBlaSqu3`), and above all that they clearly state which effect our procedure makes;
- in order to communicate the **strategy** we consider to solve our problem;
and as a consequence of all this: in order to **write more powerful programs**.

During next exercises, we will write a better version of `DrawBlackSquareSide3`, dividing every part of the program in smaller procedures.

To do this, we will suggest the following strategy: build the square like three lines of three stones, one on top of the other.

It is obvious we will need a command to draw a line, so let's start from there.

> Write a procedure `DrawBlackLine3` which, like its name shows, “draws a line” dropping 3 black consecutive stones to the East.

**Note:** From now on, unless the contrary is indicated, the “program” is done by us. So you just have to write the procedure.