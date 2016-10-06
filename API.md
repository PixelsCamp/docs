# API endpoint

    https://api.pixels.camp

## Authentication 

    POST /users/auth

    You will need to send the following header 'Authorization: <auth_token>'

    You will receive the user data, and cookie named sessionid, this cookie should be used for authenticated requests


## User private info ( Authenticated )

    GET /user/me

## List users ( Non authenticated )

    GET /users/[?count=0&offset=10]

    You will receive a list of users


## User public data ( Non authenticated ) 

    GET /users/:login

    You will receive the user public data

    
## List badges ( Non authenticated )

    GET /badges/list


## List badges owners ( Non authenticated )

    GET /badges/owners/:badge_type


## Redeem a badge ( Authenticated )

    GET /badges/redeem/:login/:redeem_code



Feel free to contribute
