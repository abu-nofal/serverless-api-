

# serverLess API

---

## i worked with my partner munther and thaer 
## deploy link :

**[AWS API](https://fhsq285xae.execute-api.us-east-1.amazonaws.com/people)** 

**[Pull Request](https://github.com/abu-nofal/serverless-api-/pull/1)** 


---

## Routes:
`/POST` - create new one using req body

**https://fhsq285xae.execute-api.us-east-1.amazonaws.com/people**
```
{
    "name":" " ,
    "age" :12 
}
```

`/GET `- get all or include an id parameter to get one

`/PUT` - requires an id parameter and a body including name and age
**https://fhsq285xae.execute-api.us-east-1.amazonaws.com/people/{id}**

`/DELETE` - requires id parameter
**https://fhsq285xae.execute-api.us-east-1.amazonaws.com/people/{id}**


---

**i take it from ibrahem**

## UML Diagram:
![](https://raw.githubusercontent.com/ibrahemomari/serverLess/main/sreverLess.png)