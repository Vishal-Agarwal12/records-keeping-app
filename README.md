Link of the Website: https://record-keeping-app1.netlify.app/

I have used useState Hook because it allows us to track state in a function component.

Tech Stack Used: HTML, CSS, Javascript, Bootstrap, Reactjs, Material UI.

I have also used Flatuicolors, Shadowincss to add Some good colors and a Shadow Effect in cards.


Run npm install to install necessary packages for this project to run.
This is will actually look in package.json file and install required packages and node_modules.




React provides a bunch of standard in-built hooks:

useState: To manage states. Returns a stateful value and an updater function to update it.
useEffect: To manage side-effects like API calls, subscriptions, timers, mutations, and more.
useContext: To return the current value for a context.
useReducer: A useState alternative to help with complex state management.
useCallback: It returns a memorized version of a callback to help a child component not re-render unnecessarily.
useMemo: It returns a memoized value that helps in performance optimizations.
useRef: It returns a ref object with a .current property. The ref object is mutable. It is mainly used to access a child component imperatively.
useLayoutEffect: It fires at the end of all DOM mutations. It's best to use useEffect as much as possible over this one as the useLayoutEffect fires synchronously.
useDebugValue: Helps to display a label in React DevTools for custom hooks.
