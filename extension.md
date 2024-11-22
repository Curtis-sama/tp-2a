# TP : Requêtes sur une API publique

 1. Requête GET - Commentaires
- URL : `GET https://jsonplaceholder.typicode.com/comments`
- Réponse : [
    {
        "postId": 1,
        "id": 1,
        "name": "id labore ex et quam laborum",
        "email": "Eliseo@gardner.biz",
        "body": "laudantium enim quasi est quidem magnam voluptate ipsam eos\ntempora quo necessitatibus\ndolor quam autem quasi\nreiciendis et nam sapiente accusantium"
    },
    {
        "postId": 1,
        "id": 2,
        "name": "quo vero reiciendis velit similique earum",
        "email": "Jayne_Kuhic@sydney.com",
        "body": "est natus enim nihil est dolore omnis voluptatem numquam\net omnis occaecati quod ullam at\nvoluptatem error expedita pariatur\nnihil sint nostrum voluptatem reiciendis et"
    },
    {
        "postId": 1,
        "id": 3,
        "name": "odio adipisci rerum aut animi",
        "email": "Nikita@garfield.biz",
        "body": "quia molestiae reprehenderit quasi aspernatur\naut expedita occaecati aliquam eveniet laudantium\nomnis quibusdam delectus saepe quia accusamus maiores nam est\ncum et ducimus et vero voluptates excepturi deleniti ratione"
    }
2. Requête POST - Todos
- URL : `POST https://jsonplaceholder.typicode.com/todos`
params:
id
title
completed

3. Requête PATCH - Posts
- URL : `PATCH https://jsonplaceholder.typicode.com/posts/{1}`

4. Requête GET - Commentaires d'un Post (ID = 1)

- URL : `GET https://jsonplaceholder.typicode.com/comments?postId=1`

5. Requête GET - Photos d'un Album (ID = 2)
- URL : GET `https://jsonplaceholder.typicode.com/photos?albumId=2`

  