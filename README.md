# React 12 - Lifting State Up - Challenge

The link of the app:

https://practical-lewin-00c8a2.netlify.com

As usual, you'll find all the components under the `src` folder:
* `App`: "root" component (other "dummy" components are provided)
* `TabSelector`: allows to select a tab

You have to modify the components, so that:
* the `activeId` is present only in `App` component's state,
* it is passed to `TabSelector`,
* the method allowing to change `activeId` is in the right place