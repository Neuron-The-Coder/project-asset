
<div class="title">Simshop API</div>

# Introduction
This is a SimShop API that you can fetch using link below

`http://localhost:8000/api/simshop`

# Return Value
The return value will be the category, id, name, image URL, description, stock, and price.

# Parameters and Queries
We can change the return value using queries available from the server. This parameter is available either for GET or POST request.

* id (Integer)
  Search for specific id. If id was not found, it will return nothing. Invalid value will not be accounted.
* limit (Integer)
  How much data will be returned. Invalid value will not be accounted.
* random (1)
  If the data should be randomized in order. Other than 1 will be sorted by ID
* name (string)
  Finds a product according to name.

# Example
`http://localhost:8000/api/simshop?id=2`
<pre id="preFetch" url="http://localhost:8000/api/simshop?id=2"><code id="codeFetch"></code></pre>
