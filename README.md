
Created with
`npx create-cljs-project <project-name>`
And then added deps.edn for Cursive support as per:
https://andrearichiardi.com/blog/posts/clojurescript-cursive-shadow-setup.html

Pre-requisites:
    npm
    Java
    Clojure

To begin the build process
 `npx shadow-cljs watch frontend`
 
Open browser at:
[http://localhost:8080](http://localhost:8080)

Add run configuration: Clojure REPL, Remote, nREPL, localhost:9000
Run it.

`(shadow/repl :frontend)`
`(println "Hello")`

"Hello" should appear in the browser console log.