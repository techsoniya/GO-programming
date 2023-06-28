package main
import "fmt"
func main(){
    //declare and initialize a map
    myMap:=make(map[string]int)
    //insert key value pairs into the map
    myMap["apple"]=1
    myMap["banana"]=2
    myMap["orange"]=3
    
    //accessing value using the keys
    appleValue:=myMap["apple"]
    bananaValue:=myMap["banana"]
    fmt.Println("value of apple:",appleValue)
    fmt.Println("value of banana:",bananaValue)
    
    //updating value
    myMap["apple"]=5
    fmt.Println("updated value of apple",myMap["apple"])
    
    //deleting a key value pair 
    delete(myMap,"orange")
    fmt.Println("after deleting orange: ",myMap)
    
    //checking exixtence of a key
    value, exists:=myMap["banana"]
    if exists{
        fmt.Println("value of banana: ",value)
    }else{
        fmt.Println("banana not found in the map")
    }
    
    //itirating over the map
    for key,value:=range myMap{
        fmt.Println("key: ",key,"value:",value)
    }
    //length of the map 
    fmt.Println("length of map:",len(myMap))
    
}
