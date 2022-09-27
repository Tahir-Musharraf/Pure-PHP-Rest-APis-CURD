# Run the file on PHP Server

## show_post
http://localhost/set-apis/apis/posts/read.php

##  show single post by id
http://localhost/set-apis/apis/posts/single_post.php

    defaultiD = 1
### Parameters:
    {"id": "INT"}

## add_post
http://localhost/set-apis/apis/posts/add_post.php
### RAW DATA IN BODY
    "balance_name": "TEXT",
    "balance_price": INT

## update_post
http://localhost/set-apis/apis/posts/update_post.php
### RAW DATA IN BODY
    "balance_id", "INT (balance_id of the post to need to be updated)"
    "balance_name": "TEXT",
    "balance_price": INT

## del_post
http://localhost/set-apis/apis/posts/del_post.php
### RAW DATA IN BODY
    "balance_id" : INT (balance_id of the post to need to be deleted)
