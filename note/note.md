#### javascript
https://github.com/Susan-Andrews/Javascript  
#### react 
###### conditional rendering 

```
const ConditionComp = () => {
  const [isLoggedIn,setIsLoggedIn] = useState(false)

  return (
    <div>
        <h2>Conditional Rendering Example</h2>
        { isLoggedIn ? (
          <h2 className="welcome">Welcome, User!</h2>
      ) : (
        <button 
          className="loginButton"
          onClick={()=>setIsLoggedIn(!isLoggedIn)}>Login</button>
      )}
    </div>
  );
};
```
