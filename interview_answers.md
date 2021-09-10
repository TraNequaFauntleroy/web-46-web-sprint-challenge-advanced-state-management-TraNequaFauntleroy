# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
    A: Context API was created to share state down a component tree, without the need to prop-drill.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    A: Actions: carries a payload of information from your application to store.
    Reducers: a function that takes an action and the previous state of the application and returns the new state
    Store: an immutable object tree in Redux that holds the application's state.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
    A: Redux Thunk is a middleware that allows us to call the action creators that return a function, which takes the store's dispatch method as the argument and which is afterwards used to dispatch the synchronous action after the API or side effects has been finished.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
    A: My favorite state management system is redux. I personally hate prop-drilling so being able to contain all my props in a centralized place is ideal. I also love how connect and mapStateToProps simplifies passing props to components.