
<div class="title">Castawiki API</div>
<div class="credit">From The Sims 2 Castaway PS2 games by The Electronic Arts</div>

# Introduction
This is a Castawiki API that you can fetch using link below

<p><code class="api-url"></code></p>

# Return Value
The return value will be the category, id, name, image URL, and description.

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
<p><code id="example-url"></code></p>

<pre id="pre-fetch" url=""><code id="example-fetch"></code></pre>
