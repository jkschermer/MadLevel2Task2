# MadLevel2Task2
layout setup

**MAD Level 2 questions**

**What is the difference of a staggered grid comparing to a normal grid?**

Extension to gridview, but in this each grid is of varying size. Staggered grid view shows asymmetric items in view. In a normal grid, each one is of the same size. This one shows items symmetrically in view.

**What is the purpose of logcat?  **

Command line tool that dumps a log of system messages, including stack-traces when the device throws an error and messages that you have written from your app with the log class.

**What kind of gestures are available?**

- Pinch
- Double tap
- Scrolls
- Long presses
- Flinch

**What was the predecessor of the recyclerview?**

Listview and gridview

**What is the difference between a Toast and Snackbar ?**

A toast is similar to a pop-up displayed with a message. It only remains visible for a short time. On the other hand a snackbar is being used to show messages in the bottom of the application with swiping enabled. It may contain an optional button.

**What is the purpose of the existence of &quot;optionals&quot; (represented by the &quot;?&quot; mark) in the Kotlin language? And what does the &quot;!!&quot; mark mean?**

To distinguish references that can hold null values, a variable with a question mark behind, would be able to hold a null value. On the other hand variable without that question mark would not be able to have a null value. They can also be used in conditions, where the variable could be a null value or not.

The mark !! is a not null assertion operator. It converts any value to a non-null type and throws an exception if the value is a null

**What is the purpose of a &quot;data class&quot; in Kotlin?**

- being used to hold state/data
- Class with additional functions
- Don&#39;t need to write generate all the lengthy boilerplate code

**What is a &quot;companion object&quot; in Kotlin? Explain the difference (if any) with a &quot;static final&quot; and with a &quot;val&quot;, and when to use which constant type.**

If you need a function or a property to be tied to a class rather than to instances of it, you can declare it inside a companion object. It is a singleton and its members can be accessed directly via the name of the containing class. It is a proper object on its own and it can have it&#39;s own supertypes and you can assign it to a variable and pass it around.

One advantage that companion objects have over static values is that they can inherit from other class or implement interfaces and generally behave like a singleton. They are beneficial for encapsulating things.

**Explain what &quot;StaggeredGridLayout&quot; is.**

It is a layoutmanager, similar to a gridview but in this grid each view has it&#39;s own size. It supports both vertical and horizontal layout.
