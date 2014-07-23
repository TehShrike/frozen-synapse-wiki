title: API

A third party web based API exists which 3rd party applications can use to extract data from the game.



## <span class="mw-headline" id="Using_the_API"> Using the API </span>

The API is hosted on [http://slashsrv.com/projects/fs-api/](http://slashsrv.com/projects/fs-api/).

All queries are straight forward HTTP GET requests with any parameters within the URL. All responses are either JSON or an empty page in the case of an error. In the case of errors semantically correct status headers should be returned. If you are testing API calls in your browser I highly suggest you use Firefox (or derivatives) and install the [JSONView](http://jsonview.com/) extension. This will allow your browser to nicely render the JSON, rather than offering to download the resulting document.

## <span class="mw-headline" id="Supported_queries"> Supported queries </span>

<table border="1">
<tr>
<td>**Call**
</td>
<td>**Parameters**
</td>
<td>**Description**
</td>
<td>**Returned values**
</td>
<td>**Cached time (minutes)**
</td>
<td>**Example URL**
</td></tr>
<tr>
<td>user/_username_/profile
</td>
<td>username (string) The username to look up, case-sensitive
</td>
<td>Gets the profile of a user
</td>
<td>On success a JSON object. Otherwise a 404 or 503
</td>
<td>30
</td>
<td>[http://slashsrv.com/projects/fs-api/user/Sid/profile](http://slashsrv.com/projects/fs-api/user/Sid/profile)
</td></tr>
<tr>
<td>online
</td>
<td>_none_
</td>
<td>Get the list of online players<sup>1</sup>
</td>
<td>On success an array of JSON objects<sup>2</sup>
</td>
<td>5
</td>
<td>[http://slashsrv.com/projects/fs-api/online](http://slashsrv.com/projects/fs-api/online)
</td></tr>
<tr>
<td>top_5/_type_
</td>
<td>type (string) "global", "daily" or "streak"
</td>
<td>Get the top 5 players of the specified type
</td>
<td>On success an array of strings.
</td>
<td>5
</td>
<td>[http://slashsrv.com/projects/fs-api/top_5/global](http://slashsrv.com/projects/fs-api/top_5/global)
</td></tr>
<tr>
<td>rankings/_type_
</td>
<td>type (string) "global", "daily" or "streak"
</td>
<td>Get the full rankings of the set type
</td>
<td>On success an array of objects (players)<sup>3</sup>
</td>
<td>30
</td>
<td>[http://slashsrv.com/projects/fs-api/rankings/global](http://slashsrv.com/projects/fs-api/rankings/global)
</td></tr></table>

1: It was recently found that this method does not actually return all online users. For some reason the game doesn't list all the online users (it's not separated by sub-servers as originally thought), but only some of the users. This call returns the same list a player would see, which is not necessarily who is actually online.

2: When the server population is above a certain threshold (currently 100) the game doesn't display player levels of the people online. This is why in this case the API displays the level as zero, there is not much that can be done about this. The API should not change the structure of the JSON response depending on server population and certainly shouldn't want to query each profile to get their true level. Just know that if the user level is zero that's because the server didn't give the API anything.

3: JSONView (which is recommended above to view these results), seems to have a maximum limit to how much JSON it will parse. This list can exceed that limit. The JSON returned by the API **is correct and valid**, it's the fault of JSONView. Try using wget/curl and you'll see the JSON is complete.

## <span class="mw-headline" id="Error_handling"> Error handling </span>

In the case of an invalid query or invalid parameters (such as looking up the profile or a non-existent user) a blank 404 page will be returned. A 503 can also be returned if the API is currently overloaded, in such a case wait a few seconds are try again.

## <span class="mw-headline" id="Feedback"> Feedback </span>

Sid (usually on IRC) is the sole developer and maintainer of this API. If the API is down or something bad has happened inform Sid, if away leave a private message on IRC.

Please do not hammer the API. Caching is done to mitigate hammering, but it's still very possible for this service to be abused, which may lead to it being pulled.

Feature requests should also go to Sid, although are likely to be declined.

<!-- 
NewPP limit report
Preprocessor node count: 15/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:238-0!*!*!!en!*!* and timestamp 20140722140010 -->