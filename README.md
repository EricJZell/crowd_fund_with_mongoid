# Notes to Self:

* Start the mongodb server with `$ brew services start mongodb`

In the rails console, to use direct mongodb syntax:

* `db = Mongoid::Clients.default`

* `posts_collection = db[:posts]`

* `posts_collection.find({body: /ello/})`
