Lesson 2.04 — Mixing Types & Casting
====================================================================================================

Overview
--------
### Objectives — _Students will be able to…_
- **Describe** which types automatically convert into others when appearing together
- **Predict** how an expression with mixed types will evaluate
- **Convert** types by casting

### Assessments — _Students will…_
- **Use** rules of precedence to correctly write code that yields a given answer
- **Create** their own expressions
- **Predict** output by completing and trading worksheets

### Homework — _Students will…_
- **Read** BJP 2.3 up to “Nested for Loops”
- **Complete** self-check question 18
- **Finish** the worksheet if not completed in class


Materials & Prep
----------------
- **Projector and computer**
- **White paper** **and** **markers**
- **Classroom copies** of [WS 2.4][], [Poster 2.4][]
- **Zombie/werewolf video** (<https://www.youtube.com/watch?v=ZL-58z3HxUI&feature=youtu.be&t=2m41s>)
  - Probably want to play on mute!
- **Unicorn image**
  ([http://1.bp.blogspot.com/\_WOWQJUlRtKQ/TRD5BW8v5GI/AAAAAAAABAY/llLQ4VSCskc/s1600/moon-wallpaper 9.jpg](http://1.bp.blogspot.com/_WOWQJUlRtKQ/TRD5BW8v5GI/AAAAAAAABAY/llLQ4VSCskc/s1600/moon-wallpaper%209.jpg))


Pacing Guide
------------
| Section                      | Total Time |
|------------------------------|-----------:|
| Bell-work and attendance     |       5min |
| Introduction to Mixing Types |      10min |
| Activity 1                   |      15min |
| Introduction to Casting      |       5min |
| Activity 2                   |      15min |
| Turn in worksheets, wrap up  |       5min |


Procedure
---------

Today’s class introduces the concept of mixing types in an expression as well as casting. Demo these 
operations in front of the class. There are a variety of metaphors you can use to drive this point 
home if students are confused -- try talking about types as contagious.

### Bell-work and Attendance `[5 minutes]`

### Introduction to Mixing Types `[10 minutes]`

1. Here are some questions to introduce this lecture:

   - Have you needed to change a value's type?
   - What would happen if you asked a user for a number?
   - What happens when you add numbers of different types? What is the type of the answer?

2. Introduce the following concept:

   - One value will change types if we put together different types in an expression (_aka_
     “**mixing types**”):

     - If an int is placed in an expression with a double, Java converts it to a double. 
       (int values are automatically cast (widened) to double values.)

     - If a double or int is placed in an expression with a String, Java converts it to a String.

     - So: `String` > `double` > `int`

   - In Java we call this “promoting” because the double holds more information than int, and String
     holds more information than double! (We’ll learn more about what information is stored in a
     String, but for now just remember its true.)

   - Spot-check your students by asking them to name type in an example on the board:

     - `2 + 2.3` (evaluates to 4.3 because int 2 is promoted to double 2.0)

### Activity 1 `[15 minutes]`

1. Have students begin WS 2.4 alone or quietly in pairs.

2. Students WILL get confused on the mixed type String questions.

   a. We recommend that you cover an example or two of these on the board, and you may find that you
      have to switch to whole group instruction for the majority of these.

   b. Your priority should be to thoroughly complete several examples, and to see that students can
      complete these questions correctly without your aid. If you need to slow down your pace, we recommend doing it.

3. If students are completing the questions on-pace, bring the class together for another round of
   whole-group instruction.

### Introduction to Casting `[5 minutes]`

1. Introduce the concept of **casting** by asking students what to do if they really want to
   preserve one type over another (the int type)?

2. Review/repeat the earlier concepts by asking students: How do we convert doubles to
   ints?

3. Introduce casting 

   - To keep a value from being promoted, you can CAST it by putting the name of the type you want 
     in front of the value you want to convert (cast):

     `(int) 42.9` ⇒ `42`

     **IMPORTANT**: Java just cuts off that extra part after the decimal—it always rounds toward
     zero.

   - BUT casting (int)str or (double)str on a String str doesn’t work.

### Activity 2 `[15 minutes]`

---

#### Emphasize with students...

#### Content - Management of Complexity

This activity will provide you with some experience with mixing variables and casting. As you create larger programs for other people, you will be manipulating different kinds of data and information. This will add complexity to your program, which is why it’s important to learn how to handle the variety of data types used in your program.

Imagine you ask a user to enter their age, you would expect them to enter an integer such as “34” or “14”. But it might surprise you when a user types “Fifteen”, “Sixty-seven” or “9.5”. To avoid your program from crashing, you want to be able to add complexity to the program so that you can handle these errors effectively. 

---

1. Have students return to WS 2.4.

2. Work through 1 or 2 problems as a whole group before you leave students to their own devices.

3. If student frustration levels are high, bring the class back to whole-group and work through a
   few more examples slowly and thoroughly. If you need to add an analogy (contagious infection, zombies, etc) or have students flip
   through their books again, you should do so at this point.

### Turn in Worksheets, Wrap Up `[5 minutes]`
At the end of class, collect the completed worksheets.

### College Board Topic Question
After this lesson, students will be able to answer most of the questions from the College Board Unit 1 Topic Questions 1.5: Casting and Ranges of Variables.

Accommodation and Differentiation
---------------------------------
If you have students who are speeding through this lesson, you should encourage them to try examples with more types
to see which types "take over." If a student has a good grasp early on, you can ask them to make a poster to keep on
the wall. Even if you do not have a student do this for you, we HIGHLY recommend making a poster of this sort.
Students do not forget it! If all else fails, you can use the image saved as Poster 2.4.

Video
-----
- CSE 142, Casting (18:39–31:29)<br>
  <https://www.youtube.com/watch?v=0eUm1RFGkWw&start=1119>

- CS Homework Bytes, _Type Conversations, with Kristin_<br>
  <https://www.youtube.com/watch?v=y-4vMMeBcAc>


Forum discussion
---------------------------
[Lesson 2.04 Mixing Types & Casting (TEALS Discourse account required)](http://forums.tealsk12.org/c/unit-2/2-04-mixing-types-casting)


[WS 2.4]:   https://raw.githubusercontent.com/TEALSK12/apcsa-public/master/curriculum/Unit2/WS%202.4.docx
[Poster 2.4]:    https://raw.githubusercontent.com/TEALSK12/apcsa-public/master/curriculum/Unit2/Poster%202.4.docx
