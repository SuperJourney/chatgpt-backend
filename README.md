# 
ChATDEMO的演示后端环境

# 
get chats
response: 
```
[
    {
        "id":"1xx123",
        "created_at":123,
    }
]
```

get chats/:1
{
    "id":"1xx123",
    "context":[
        {
            "role":"system",
            "context":"x12312312312\n"
        },
    ]
}
POST chats 

{
    "context":[
        {
            "role":"system",
            "context":"x12312312312\n"
        },
    ]
}

PUT chats/:1

{
    "id":"1xx123",
    "context":[
        {
            "role":"system",
            "context":"x12312312312\n"
        },
    ]
}


DELETE chats/:1

