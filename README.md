# mean-market-web

[Video ref => Creating a Simple Web Application(Shopping Website) from Scratch [#1] | Angular + Material | Mock-up](https://www.youtube.com/watch?v=41aGgttr8UU&t=100s&ab_channel=ShaheerShukur)


### Create angular project
```
ng new market
```
- set Y for genreate router
- set Css for template

### angular command 
```
ng serve \\ run angular app
ng serve --open --port 5000 \\ run and specific port then open in web browser
```

- Add angular material
```
ng add @angular/material
// chose Custom 
// Set up global Angular Material typography styles? => Y
// Set up browser animations for Angular Material? => Y
```


[Video ref => Quick UI using Angular Material Schematics [#2] | Front end development | Web Application](https://www.youtube.com/watch?v=dcACk0WTqNc&ab_channel=ShaheerShukur)


### Generate navigation nav
```
ng generate @angular/material:navigation nav
/*
==> Result after generate <==
CREATE src/app/nav/nav.component.html (929 bytes)
CREATE src/app/nav/nav.component.spec.ts (1227 bytes)
CREATE src/app/nav/nav.component.ts (578 bytes)      
CREATE src/app/nav/nav.component.css (193 bytes)  
*/

```

### Generate Dashboard
```
ng generate @angular/material:dashboard home
```


