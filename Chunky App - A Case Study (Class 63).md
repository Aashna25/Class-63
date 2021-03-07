Chunky App - A Case Study (Class 63)

● Explore case study of an app designed for students with reading difficulties. 

● Design wireframe for the app (including UI/UX). 

● Collect input from the user and display it on the screen.

There are 44 different kinds of sounds in english - called phonemes. Each word is made up of a combination of these sounds. For example: The word cat is made up of sounds \c\ \a\ \t\

A phoneme could be made up of a combination of one or more than one letter.

Through minimal practice, most of us have learned to identify these patterns of letters which make up a phoneme, identify them in words and combine them to make words.

Pattern recognition is so natural for us that we have learned to do it almost intuitively.

However, students with reading difficulties find it very hard to identify these patterns. They need repeated practice of breaking down the words into the different chunks, identifying the phoneme sound associated with each chunk, combining the phoneme sounds to pronounce a word.

Often these students need special teachers who would be patient and not get irritated with the students' failed attempts to recognize the chunks and phonemes. With enough practice, these students can read as well as anyone else.

In fact, you can read a little about Patricia Polocco who had a reading disorder but she went on to become a popular English author who has written some famous books and stories for children.

Not everyone is lucky to get such patient teachers though.

In this and coming few classes, we are going to build a tool/app for students with reading disorders where they can type a word as input. The app will then break down the word into chunks. The student will be able to tap on each chunk to hear a sound associated with each chunk. They can then join the chunks to pronounce a word.

Students with reading difficulties or early readers will be able to use the tool to practice reading words. We can call this app - Monkey Chunky - from the name of the trick used to chunk words into smaller units

What do we do before actually going on to build the app?

Building a wireframe is also called designing the User Interface (UI) or User Experience (UX). It is a crucial part of any app. It defines how your app will be used by the user and how they will experience it.

Like coding, designing the user interface/user experience (UI/UX) is also an iterative process

We design a user interface and implement it in the app. After implementation and testing, we might realize that the user experience could be made better by tweaking a few features in our app and we make those changes to the UI/UX. This can go on till we are completely satisfied.

Can you spend some time designing the wireframe for our Monkey-Chunky App? You can use a paper and pen to draw the wireframe.

Allow the student some time to draw a wireframe for the monkey chunky app.

We can start our project either on Expo snack online as we were doing for previous projects OR we can do so locally using expo-cli tools we installed in the last class.

To start the project locally - you need to type: expo init <project name>

Choose a blank project and let expo install all the expo libraries for the project.

we have seen several in-built React native components so far. We have also built some of our own components like AppHeader.

There are other developers who have also built several react native components and open-sourced them as React Native UI libraries. We can directly import these components in our project and use them. The advantage of using these components is that they are well-designed and thoroughly tested.

One of the popular React Native UI libraries which developers like to use is ‘React Native Elements’. You can learn about the different components available and their props, examples on how to use them through the documentation available.

Let's use one of their components, ‘Header’.

Note: If doing this locally, they have to first use ‘npm install react-native-elements’ to install the react-native-elements library.

Let's use the ‘Header’ component in our App. use the Header Component by referring to the docs and coding in the app.

Now, we need to use a component which will take input from the user. There is a React native component called ‘TextInput’ for this. Using it is slightly trickier.

Can you collect input from the user and display it in your app.?

We are going to use a new Component called ‘TextInput’ which is part of React Native library.

We have to create a state which constantly updates when the user types text as input. The value of ‘TextInput’ should be the same as ‘text state’.

Let's create a button called ‘Go’ button which updates ‘displayText’ to the same value as text when the user presses this button