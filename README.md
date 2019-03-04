# Notable - [Watch the full tutorial!](https://youtu.be/fsCjFHuMXj0)

available all CRUD operations.
change your config/db.js with your own mlab collection id.

to change your APi call for your needs, in ```app/note_routes.js```
change the variable ```const note = ...``` object as your desire.
for example, to construct a POST request for user in social network' change to:
```
{
    username: req.body.body,
    imageurl: req.body.imgurl,
}
```
and so on...