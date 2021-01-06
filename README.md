# Dating App .NET Angular Project

This is my Full stack app built following Neil Cummings' [Build an app with ASPNET Core and Angular from scratch](https://www.udemy.com/course/build-an-app-with-aspnet-core-and-angular-from-scratch/?utm_source=adwords&utm_medium=udemyads&utm_campaign=WebDevelopment_v.PROF_la.EN_cc.UK_ti.8322&utm_content=deal4584&utm_term=_._ag_73899898953_._ad_375956900774_._kw__._de_c_._dm__._pl__._ti_dsa-774930035449_._li_1007326_._pd__._&matchtype=b&gclid=Cj0KCQiA3NX_BRDQARIsALA3fILf8LxvbyX5G6y2p9tFjjbOL_nSQ5xoWY2HdF-V-gaQ8bZQ44LXzyIaAuU9EALw_wcBm)
with .NET 5 API using SqlLite/Postgres as a database and Angular for the frontend.

### Features:
* Drag and drop photo upload integrating into a cloud platform Cloudinary
* Filtering, sorting and paging of data
* Identity and Role Management
* Authentication using JWT Authentication tokens
* Persist data using Entity Framework Core
* Using SignalR for real time presence and live messaging between users

### Project setup and use
#### Backend
Install required modules, create and seed database.

```net
cd API
dotnet run
```

#### Frontend
```js
cd client
ng serve
```
Navigate to http://localhost:4200/
