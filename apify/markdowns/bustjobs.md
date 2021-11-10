
<div class="title">Bustjobs API</div>
<div class="credit">From The Sims Bustin Out by EA and Maxis games</div>

# Introduction
This is a Bustjobs API that you can fetch using link below

<p><code class="api-url"></code></p>

# Return Value
The return value will be the category, job, description, and salary.

# Parameters and Queries
We can change the return value using queries available from the server. This parameter is available either for GET or POST request.

* career (string)
  Get a specific jobs according to category. Category available as follows (**Title Case** and **snake_case** are allowed):
  * Movie Star (movie_star)
  * Mad Scientist (mad_scientist)
  * Gangster (gangster)
  * Fashion Victim (fashion_victim)
  * Paramilitary (paramilitary)
  * Counter Culture (counter_culture)
  * Jock (jock)
  * Artist (artist)
  * Computer Geek (computer_geek)
  * Rockstar (rockstar)
  * Swindler (swindler)
  * Slacker (slacker)
* job (String)
  How much data will be returned. Invalid value will not be accounted.
* limit (integer)
  Limits the amount of query sorted by ID. Any invalid number will be treated as no limit.

# Example
<p><code id="example-url"></code></p>

<pre id="pre-fetch" url=""><code id="example-fetch"></code></pre>
