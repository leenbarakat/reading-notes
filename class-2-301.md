

![l](https://miro.medium.com/max/2000/0*0saPKFiTUk6W3FYp)

# What happens first, the ‘render’ or the ‘componentDidMount’?

When a component is mounted it is being inserted into the DOM. This is when a constructor is called. componentWillMount is pretty much synonymous with a constructor and is invoked around the same time. componentDidMount will only be called once after the first render.

# What is the very first thing to happen in the lifecycle of React?

The **static getDerivedStateFromProps** is the first React lifecycle method to be invoked during the updating phase.

static **getDerivedStateFromProps** is a new React lifecycle method as of React 17 designed to replace **componentWillReceiveProps**.

Its main function is to ensure that the state and props are in sync for when it’s required.

static **getDerivedStateFromProps()** takes in **props** and **state**

Why exactly is this lifecycle method important?

 While static **getDerivedStateFromProps()** is a rarely used lifecycle method, it comes in handy in certain scenarios.

Remember, this method is called (or invoked) before the component is rendered to the DOM on initial mount.

![img](https://i.stack.imgur.com/tQhSG.png)

##  Put in order : **componentDidMount, render, constructor, componentWillUnmount, React Updates**


- constructor

- render

- componentDidMount

- React Updates

- componentWillUnmount

## What does componentDidMount do?

The componentDidMount() method allows us to execute the React code when the component is already placed in the DOM (Document Object Model). This method is called during the Mounting phase of the React Life-cycle i.e after the component is rendered.

All the AJAX requests and the DOM or state updation should be coded in the componentDidMount() method block. We can also set up all the major subscriptions here but to avoid any performance issues, always remember to unsubscribe them in the componentWillUnmount() method.

