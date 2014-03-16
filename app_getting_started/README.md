# Getting Started - App 0

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Lets do it!
```s
##| server.R
shinyServer(function(input,output) {})
```

```s
##| ui.R
shinyUI(pageWithSidebar(
  headerPanel("My first Shiny app"),
  sidebarPanel(),
  mainPanel()
  ))
```
![logo](https://github.com/wsurles/shiny_workshop/blob/master/app_getting_started/www/rally_logo.png "Rally Logo")

![logo](files/www/rally_logo.png)


[http://www.githubarchive.org](http://www.githubarchive.org/)

Open-source developers all over the world are working on millions of projects: writing code & documentation, fixing & submitting bugs, and so forth. GitHub Archive is a project to **record** the public GitHub timeline, **archive it**, and **make it easily accessible for** further analysis.

![Stats](http://www.stathat.com//graphs/39/33/0b63991416f6b680e69f017a2c12.png?1340405820)

----

Looking for the [daily top new & watched repository](http://us5.campaign-archive2.com/home/?u=439aa16a39e4b10e0b65ff2ef&id=0b82fec5c2) reports? [Sign up here](http://githubarchive.us5.list-manage.com/subscribe?u=439aa16a39e4b10e0b65ff2ef&id=0b82fec5c2).

----

GitHub provides [18 event types](http://developer.github.com/v3/activity/events/types/), which range from new commits and fork events, to opening new tickets, commenting, and adding members to a project. The activity is aggregated in hourly archives, which you can access with any HTTP client: