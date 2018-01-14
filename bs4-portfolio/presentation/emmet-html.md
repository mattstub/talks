# Header
```
header.jumbotron.jumbotron-fluid
    div.container
        h1.display-1    "Matt Stubenhofer"
        h4              "Aspiring Web Developer"
```

# About
```
section.container#about
    h2.text-right-display-4     "Who's this guy?"
    p.text-right                "lorem50"
```

# Projects
```
section.container-fluid#projects
    div.container
        h2.display-3.text-center        "Projects"
        div.container.app-wrapper
            div.row.container
                div.col-md-4
                    img.img-responsive
                div.col-md-8
                    div.row
                        span.col-sm-8.app-title      "JS Calculator & Pomo Clock"
                        span.col-sm-4.btn-group.align-top
                            button.btn.btn-outline-dark.btn-small   "Code"
                            button.btn.btn-outline-dark.btn-small   "App"
                    div.row
                    -- Progress Bar Insert --
                        i.ion-social-html5          bg-danger       49.2%
                        i.ion-social-javascript     bg-warning      36.1%
                        i.ion-social-css3           bg-info         14.7%

                        i.ion-social-nodejs         bg-success      21.3%
                        i.ion-social-angular        bg-danger       60.2%
                        i.ion-social-sass           bg-info         18.5%
```

# Footer / Contact
```
footer.container-fluid#contact
    div.container
        h3.text-center.display-4        "Contact Me!"
        div.row.contact-icons.justify-content-center
            i.ion.android-mail
            i.ion-social-facebook
            i.ion-social-twitter
            i.ion-social.github
            i.ion-social-twitter
            i.ion-social-linkedin
```
