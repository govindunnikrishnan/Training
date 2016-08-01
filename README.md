###Training- Day 3


--Worked with Middleman
 Directions to use middleman
 1. $ gem install middleman  -Install the gem
 2. $ middleman init project -run middleman init my_project to create a new Middleman skeleton site from the command line.
 3. $ middleman server -run the middleman server and to view your site
 
 
--Worked in Haml
 Directions to use Haml
 1. $ gem install haml -install the Haml gem
 2. $ haml input.haml output.html -To run Haml from the command line
 3. To use Haml with Rails, add the following line to the Gemfile: gem "haml" 
 
 
--Haml template in Middleman
 Directions
1. set :haml, { :ugly => true, :format => :html5 }   -to set option for haml template in your config.rb
2. restart middleman server to access your site.
