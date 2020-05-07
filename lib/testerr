require 'nokogiri'
require 'open-uri'

html = open("http://learn-co-curriculum.github.io/site-for-scraping/courses")
doc = NOKOGIRI::HTML(html)
  courses = doc.css(".posts-holder").text
  puts courses
