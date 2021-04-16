# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

Context API solves the problem of prop drilling through components.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Action define what type of action to take when entering a new state, reducers mutaate a copy of the state data, the store is the initial state data that is used to be mutated when state data changes.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

Uses async logic to interact with our store. Allowing us to create an action for each async action, makes it easier to debug our code.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

Context is my favorite because it provides a way to pass data through the component tree without having to pass props down manually.
