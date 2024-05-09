> mutation{
    addAuthor(name:"Satyam Tiwari",age:24){
        id,name,age
    }
}

> query{
    authors{
        name,age,
        books{
            name,
        }
    }
}# graphql
# graphql
