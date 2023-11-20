Here are some quick steps for creating an O(fast) lesson

1. Create a directory with all of the lesson components

   - you can find instructions on how to make the lesson components [here](creating_components)

2. Create a `lesson.json` which will contain an array of how to order the components on the page in your lesson [lesson.json](dynamic_programming/lesson.json)

   - the `lesson.json` file should contain an array of objects which have a field for the filename along with a field for the type of file which is one of:
     "reading",
     "mcq",
     "fitb"

3. Add the directory name to the [lessons.json](lessons.json) file
4. Make a pull request with the markdown file(s) you've added
5. The pull request with be reviewed by an O(fast) team member, and you'll have the chance to update the pull request and make any requested changes
