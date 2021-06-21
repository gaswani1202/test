## Calculate Greatest Common Divisor(G.C.D.)

Returns greatest common divisor for the entered list of integers.


**URL**
/gcd/:numbers

**Method**
GET

**URL Params**

 *Required*
 
 numbers=[integer]

**Data Params**
None


**Success Response**
 The result of [2, 4, 6] is 2

** ErrorResponse **
{
    "timestamp": "2021-06-21T04:33:17.686+00:00",
    "status": 400,
    "error": "Bad Request",
    "path": "/gcd"
}


**Sample Call**
http://localhost:9100/gcd/?number=10,20,30

Output:
The result of [2, 4, 6] is 10