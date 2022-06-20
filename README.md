# graphql-query-mutation-beginner

# {
#   getAllUsers {
#     firstName
#     lastName
#     email
#   }
# }

# mutation {
#   createUser(firstName:"Nikhil", lastName:"Andola", email:"nikhil@gmail.com",password:"nikhil"){
#     firstName,
#     lastName,
#     email
#   }
# }

query {
	getAllUsers {
    id
    firstName
    lastName
    email
    password
  }
}
