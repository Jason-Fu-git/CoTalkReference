# Get member list

<api-endpoint openapi-path="../cotalk.yaml" endpoint="/api/chat/{chatid}/members" method="GET">

<response type="200">

<sample>
{
    "code" : 0,
    "info" : "Success",
    "members": [
        {
            "user_id" : 1,
            "user_name" : "Plato",
            "user_email" : "Plato@163.com",
            "avatar" : "{FILE BINARY}",
            "privilege" : "member",
        },
        {...},
        ...
    ]
}
</sample>

</response>

</api-endpoint>