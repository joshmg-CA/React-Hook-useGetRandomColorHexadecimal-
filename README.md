## React-Hook-useGetRandomHexColor 

### UseGetRandomColorHex
        
The hook UseGetRandomColorHex is very easy,this hook does not recive any arguments is just for return the hex color, you just execute it hook and that is it
,this hook does not receive any arguments, it is only to return the hexadecimal color. 

example:


```javascript
const [randomHexColor]  = useGetRandomColor();           
useEffect(()=>{
  setColor(randomHexColor);
},[])    
```

#### I'll do a refactoring using the hook useCallback()

##### just copy and paste
