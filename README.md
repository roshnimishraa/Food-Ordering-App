# Mealy

## Technology Used 
1. React.js
2. express.js
3. In frontend
 Data fetching typically involves making HTTP requests using fetch methods
4. In Backend
 This server-side logic in Express.js handles data fetching and storing locally using file operations (fs module). 
 
## Features 
1. Add components for displaying products, the cart(in a modal) and a checkout form(also in a modal) 
2. Fetch the meals data from the backend and show it on the screen (GET/meals)
3. Allow users to add and remove products to/from the cart
4. Send cart data along with user data(full name,email,street,postal code, city) to the backend (POST/orders)
5. Handle loading and error states
6. Sending a POST Request with Order data 

## Workflow
1. Add the Header component
2. Add the Meals-related components and the logic to fetch meals data from a backend
3. Add Cart logic(add items to cart, edit cart items) and Checkout page logic

## Concepts Used:
1. useState hook
2. useContext hook <!-- Context features allows us to spread data into all components that needed in a very easier and re-usuable way     createContext -->
3. useReducer Hook  <!--  : It allows us to manage complex state in much simpler way and it is easier to move that state management logic out of this component function  -->
4. useContext Hook <!-- : It allows us to access to get context  -->
5. createPortal (react-dom) <!--  feature of react offers so that we can use this component from anywhere in our component tree but we always eject the dialog when its visible in a specific area of the real-dom that we as a developer controller upfront -->
6. useRef Hook <!-- to access to dialog element  -->
7. props 
8. custom hooks   <!--    useHttp.js -->
9. useEffect hook 
10. UseCallback   <!-- : so that code doesn't stuck in infinity loop  -->


