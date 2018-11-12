# un-awesome
The most shitty codes you ever seen in your entire life. 💩

Did you think that the code that you seen was terrible? Look the codes bellow and be happy with you shitty code.

## Contributing
Just send a PR

## Programming language indices

* [Javascript](#javascript)
* [Java](#java)


### Javascript

###### The Best null checking ever
```javascript

const newReply = (reply !== null) ? reply : null;
```
###### Handling errors as I handle problems in my life
```javascript
const errorHandler = () => {
  throw new Error();
};
```


###### "Yes I understood this async await thing"
```javascript
const routine = async (callback) => {
  return await userApi.get().then(()=> callback)
}
```


###### It's so clear
```javascript
const sumBy = (collection, property) => _.sumBy(collection, item => item[property]);
```



### Java

###### Really?
```java
if(computedDate != null){
    myObject.setDueDate(computedDate);
}
else{
    myObject.setDueDate(null);
}
```


###### Because we don't trust in 'Object == null'
```java
public boolean logout(String token)
{
    LogedUser user = logedUsers.remove(token);
    return (user != null) ? true : false;
}
```


###### More if's more clear
```java
boolean returns = false;

if (c.getId() != null)
  returns = true;
if (c.getName() != null)
  returns = true;
if (c.getNif() != null)
  returns = true;

if (!returns)
  throw new ValidationException("Error message");
```

###### Let's Make more for, not filter
```java 

for (invoiceDTO invoice : invoices) {
  if (invoice.status != null)
      if (invoice.status.equals(status))
         listLong.add(invoice.id);
}
