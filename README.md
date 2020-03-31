# poc-api-postman
Example Request for each API we use

How to use:
1. Get Postman: https://www.postman.com
2. Run Postman!
3. Import the relevant collection
*. Explore and Execute the relevant requests

Notes on merge:
- The collection files won't merge nicely.
- So after merge down please re-import the collection.
- And before you commit please export the collection (take default).

--- STATISTICS ---
https://covid19api.com

--- YOUTUBE ---
https://developers.google.com/youtube/v3/docs/search/list

4. Set the "key" param to your, or our, YouTube public API key (please don't commit it).
5. Run and Get items[0].id.videoId
6. Check out www.youtube.com/embed/{videoId}

Note: There are two interesting arguments I haven't set "location" and "locationRadius".
We could in theory use them to find videos posted 'close' to an hospital.

--- TODO TWITTER ---
Is it me or is Twitter reluctant to give access to APIs?
The process for requesting access is more like a wizard.
Please try this and we can come back to it:

<a href="https://twitter.com/intent/tweet?button_hashtag=thankyounhs&ref_src=twsrc%5Etfw" class="twitter-hashtag-button" data-show-count="false">Tweet #thankyounhs</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

--- TODO REDDIT ---
