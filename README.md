
(ns hello-world.core
 (:gen-class))
 (require '[clojure.string :as str])
(defn -main
 "I don't do a whole lot ... yet."
 [& args]
 (println "Hello, Team this is new!!")
 (def myset #{ 1 2 3 54 34})
 (println myset)
 (println (clojure.string/upper-case "Direct call"))
 (println (str/upper-case "this is a test"))
 (println (+ 1 4))
)
