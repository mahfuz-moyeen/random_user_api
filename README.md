# Random User API


## `npm i` & `npm start`

## link:  http://localhost:5000
* api/v1/user/random
* api/v1/user/all
* api/v1/user/save
* api/v1/user/update
* api/v1/user/bulk-update
* api/v1/user/delete

 ## Heroku host API
 * [GET_Random_User](https://random-user-api-mm.herokuapp.com/api/v1/user/random)

 * [GET_ALL_User](https://random-user-api-mm.herokuapp.com/api/v1/user/all)

 * [Post_User](https://random-user-api-mm.herokuapp.com/api/v1/user/save)  
    <pre>{
      "name": "Jimmy Perez",
      "gender": "Male",
      "contact": 12345678901,
      "address": "London",
      "photoURL": "https://i.ibb.co/ncgThwd/Jimmy-Perez.jpg"
    }</pre>

 * [Update_User](https://random-user-api-mm.herokuapp.com/api/v1/user/update)
    <pre>
    {
        '_id':"nQZYD"
        "name": "Jimmy Perez",
        "gender": "Male",
        "contact": 12345678901,
        "address": "London",
        "photoURL": "https://i.ibb.co/ncgThwd/Jimmy-Perez.jpg"
    }
    </pre>

 * [Bulk-update_User](https://random-user-api-mm.herokuapp.com/api/v1/user/update)
    <pre>
    [{
        '_id':"nQZYD"
        "name": "Jimmy Perez",
        "gender": "Male",
        "contact": 12345678901,
        "address": "London",
        "photoURL": "https://i.ibb.co/ncgThwd/Jimmy-Perez.jpg"
    },
    {
        "_id": "notjK",
        "name": "Irene Hanson",
        "gender": "Female",
        "contact": 89749740044,
        "address": "England",
        "photoURL": "https://i.ibb.co/482M2Xk/Irene-Hanson.jpg"
    }]
    </pre>

 * [Delete_User](https://random-user-api-mm.herokuapp.com/api/v1/user/delete)
 <pre>{ '_id':"nQZYD" }</pre>
