# graphql

GraphQL Server Code

Sample GraphQL queries

{
customer(id:"1"){
id
name
email
age
}
}

query{
customers{
id
name
email
age
}
}

mutation{
addCustomer(name:"Harry White", email:"hwhite@gmail.com", age:40){
id
name
email
age
}
}

mutation{
deleteCustomer(id:"J_FIwLU"){
id
}
}

mutation{
editCustomer(id:"0li6StB",age:50){
id
name
email
age
}

}
