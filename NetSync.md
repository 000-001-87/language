# NetSync
## Description
NetSync is a high-performance, sleek programming language that simplifies OOP(Object Oriented Programming) into less painful versions that are easy to code. Along with Escha, it is also one of the primary programming languages used in PureSys.
## Examples
### Hello World
```
get termFn;

Program Main(argc, argv){
    termFn.NewTerm term
    termFn.log(term, "Hello World!")
}
```
### HTTP server with Tray
```
get termFn;
get http;
get tray;

Program Main(argc, argv){
    http.Server app
    termFn.NewTerm term

    app.use(tray, handler)
    app.launch(80)

    on(app.launchSuccess, { termFn.log(term, "Server listening on port 80") })
}
tray.HTTPServer handler(req, res){
    on(req.get('/'), { return res.send("Hello World!") })
}
```
  
