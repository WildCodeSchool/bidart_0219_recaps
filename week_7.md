# Weekly recap 7
-----------------------------------------------

TEAM : Sarah, Fabien, JM and Vanessa

##AXIOS LIBRARY:

###About Axios:
Axios library is a simple complement to make HTTP requests (Ajax) using Javascript NodeJS, highly prepared to consume REST APIs.

##Axios Features:
- Make XMLHttpRequests from the browser
- Make http requests from node.js
- Supports the Promise API
- Intercept request and response
- Transform request and response data
- Cancel requests
- Automatic transforms for JSON data
- Client side support for protecting against XSRF
- Browser Support: Chrome, Firefox, Safari, Opera, Edge, IE.

##Installing Axios:
We can installing Axios library using npm:

$ npm install axios

###How to use Axios with React-app:
STEP 1: create a jsx component
STEP 2: create state of component:
```
this.state {
    example: []
}
```
STEP 3: import axios
STEP 4: create a componentDidMount() function.
STEP 5: include the code below into the componentDidMount() function
```
axios.get('API-URL')
  .then(function (response) {
    this.setState({
        example: response.data
    }): 
  })
  ```

-----------------------------------------------

