src/hoc/Aux1/Aux.js

const aux = (props) => props.children;

export default aux;


npm install --save axios

npm install --save redux-thunk

https://react-burger-app-15138.firebaseio.com/

https://react-burger-app-15138.firebaseio.com/ingredients

{

  "rules": {
  
    "ingredients": {
    
    ".read": "true",
    
    ".write": "true"
    
  },
  
        "orders": {
        
          ".read": "auth != null",
          
          ".write": "auth != null",
          
            ".indexOn": ["userId"]
            
        }
        
  }
  
}
