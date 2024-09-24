Im storing some code from the config.toml file for the menu structure. Its a great structure, but its way too complicated. I want to store it here for refrencing in the future. 

[menu]


# Main menu
[[menu.main]]
    name       = "Home"
    identifier = "menu.home"
    url        = "/"
    weight     = 1

[[menu.main]]
    name       = "Option 1: Default Page"
    url        = "/"
    weight     = 1
    parent     = "menu.home"

[[menu.main]]
    name       = "Option 2: Application"
    url        = "/"
    weight     = 2
    parent     = "menu.home"

[[menu.main]]
    name       = "Option 3: Startup"
    url        = "/"
    weight     = 3
    parent     = "menu.home"

[[menu.main]]
    name       = "Option 4: Agency"
    url        = "/"
    weight     = 4
    parent     = "menu.home"

[[menu.main]]
    name       = "Option 5: Portfolio"
    url        = "/"
    weight     = 5
    parent     = "menu.home"

[[menu.main]]
    name       = "Features"
    identifier = "menu.features"
    url        = "/img/template-easy-customize.png"
    weight     = 3

[[menu.main]]
    name       = "Shortcodes"
    identifier = "section.shortcodes"
    url        = ""
    weight     = 1
    parent     = "menu.features"
    post       = 1

[[menu.main]]
    name       = "Header variations"
    identifier = "section.headervariations"
    url        = ""
    weight     = 2
    parent     = "menu.features"
    post       = 2

[[menu.main]]
    name       = "Accordions"
    url        = ""
    weight     = 1
    parent     = "section.shortcodes"

[[menu.main]]
    name       = "Alerts"
    url        = ""
    weight     = 2
    parent     = "section.shortcodes"

[[menu.main]]
    name       = "Buttons"
    url        = ""
    weight     = 3
    parent     = "section.shortcodes"

[[menu.main]]
    name       = "Content Boxes"
    url        = ""
    weight     = 4
    parent     = "section.shortcodes"

[[menu.main]]
    name       = "Horizontal Blocks"
    url        = ""
    weight     = 5
    parent     = "section.shortcodes"

[[menu.main]]
    name       = "Pagination"
    url        = ""
    weight     = 6
    parent     = "section.shortcodes"

[[menu.main]]
    name       = "Tabs"
    url        = ""
    weight     = 7
    parent     = "section.shortcodes"

[[menu.main]]
    name       = "Typography"
    url        = ""
    weight     = 8
    parent     = "section.shortcodes"

[[menu.main]]
    name       = "Default Sticky Header"
    url        = ""
    weight     = 1
    parent     = "section.headervariations"

[[menu.main]]
    name       = "No Sticky Header"
    url        = ""
    weight     = 2
    parent     = "section.headervariations"

[[menu.main]]
    name       = "Light Header"
    url        = ""
    weight     = 3
    parent     = "section.headervariations"

[[menu.main]]
    name       = "Gallery"
    identifier = "menu.portfolio"
    url        = "/img/template-homepage.png"
    weight     = 3

[[menu.main]]
    name       = "Portfolio"
    identifier = "section.portfolio"
    url        = ""
    weight     = 1
    parent     = "menu.portfolio"
    post       = 1

[[menu.main]]
    name       = "2 Columns"
    url        = ""
    weight     = 1
    parent     = "section.portfolio"

[[menu.main]]
    name       = "2 Columns With Negative Space"
    url        = ""
    weight     = 2
    parent     = "section.portfolio"

[[menu.main]]
    name       = "3 Columns"
    url        = ""
    weight     = 3
    parent     = "section.portfolio"

[[menu.main]]
    name       = "3 Columns With Negative Space"
    url        = ""
    weight     = 4
    parent     = "section.portfolio"

[[menu.main]]
    name       = "4 Columns"
    url        = ""
    weight     = 5
    parent     = "section.portfolio"

[[menu.main]]
    name       = "4 Columns With Negative Space"
    url        = ""
    weight     = 6
    parent     = "section.portfolio"

[[menu.main]]
    name       = "Portfolio - detail"
    url        = ""
    weight     = 7
    parent     = "section.portfolio"

[[menu.main]]
    name       = "Portfolio - detail 2"
    url        = ""
    weight     = 8
    parent     = "section.portfolio"

[[menu.main]]
    name       = "About"
    identifier = "section.about"
    url        = ""
    weight     = 2
    parent     = "menu.portfolio"
    post       = 2

[[menu.main]]
    name       = "About Us"
    url        = ""
    weight     = 1
    parent     = "section.about"

[[menu.main]]
    name       = "Our Team"
    url        = ""
    weight     = 2
    parent     = "section.about"

[[menu.main]]
    name       = "Marketing"
    identifier = "section.marketing"
    url        = ""
    weight     = 3
    parent     = "menu.portfolio"
    post       = 2

[[menu.main]]
    name       = "Packages"
    url        = ""
    weight     = 1
    parent     = "section.marketing"

[[menu.main]]
    name       = "Reviews"
    identifier = "menu.allpages"
    url        = ""
    weight     = 4

[[menu.main]]
    name       = "Home"
    identifier = "section.ap-home"
    url        = ""
    weight     = 1
    parent     = "menu.allpages"
    post       = 1

[[menu.main]]
    name       = "About"
    identifier = "section.ap-about"
    url        = ""
    weight     = 2
    parent     = "menu.allpages"
    post       = 1

[[menu.main]]
    name       = "Marketing"
    identifier = "section.ap-marketing"
    url        = ""
    weight     = 3
    parent     = "menu.allpages"
    post       = 1

[[menu.main]]
    name       = "Portfolio"
    identifier = "section.ap-portfolio"
    url        = ""
    weight     = 1
    parent     = "menu.allpages"
    post       = 2

[[menu.main]]
    name       = "User Pages"
    identifier = "section.ap-userpages"
    url        = ""
    weight     = 2
    parent     = "menu.allpages"
    post       = 2

[[menu.main]]
    name       = "Shop"
    identifier = "section.ap-shop"
    url        = ""
    weight     = 1
    parent     = "menu.allpages"
    post       = 3

[[menu.main]]
    name       = "Shop - Order Process"
    identifier = "section.ap-shoporderprocess"
    url        = ""
    weight     = 2
    parent     = "menu.allpages"
    post       = 3

[[menu.main]]
    name       = "Contact"
    identifier = "section.ap-contact"
    url        = ""
    weight     = 1
    parent     = "menu.allpages"
    post       = 4

[[menu.main]]
    name       = "Pages"
    identifier = "section.ap-pages"
    url        = ""
    weight     = 2
    parent     = "menu.allpages"
    post       = 4

[[menu.main]]
    name       = "Blog"
    identifier = "section.ap-blog"
    url        = "/blog/"
    weight     = 3
    parent     = "menu.allpages"
    post       = 4

[[menu.main]]
    name       = "Blog Listing Big"
    url        = "/blog/"
    weight     = 1
    parent     = "section.ap-blog"

[[menu.main]]
    name       = "Blog"
    identifier = "menu.blog"
    url        = "/blog/"
    weight     = 5

[[menu.main]]
    name       = "FAQ"
    identifier = "menu.faq"
    url        = "/faq/"
    weight     = 6

[[menu.main]]
    identifier = "contact"
    name       = "Contact"
    url        = "/contact/"
    weight     = 7
