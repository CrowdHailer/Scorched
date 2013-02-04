Milestones
==========

Completed
---------
* Basic request handling and routing
* String and Regex URL matching, with capture support
* Implement route conditions
  * Added HTTP method condition which the route helpers depend on.
* Add route helpers
* Support sub-controllers
* Implement before and after filters with proper chaining
* Configuration inheritance between controllers - This has been implemented as the Options class.
  * Made Options class dynamic to allow conditions (and possibly more) to be inheritable.

Remaining
---------
I'm considering breaking out some of these non-core features into their own gem. From there, you may include only the extra components you intend to use.

* Add more route conditions, mainly those based on with HTTP headers e.g. content-type, language, user-agent, etc.
* Implement some form of view rendering
  * Add view helpers
    * Add helper to easily read and built HTTP query string's. Takes care of "?" and "&" logic, escaping, etc.
    
More things will be added to this list. I've just run myself out of time for now.