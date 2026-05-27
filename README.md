# fratzengeballer.eu
Ruby on Rails static Website with SVG animation of filters and Jekyll Blog gem
The SVG animate is in the SVG file inside the _include folder for it shall be inlined 
into the constructed html page and then leaves not image file in assets folder
and you have to open the SVG file in a text editor to see the <animate /> tag. 
It is all HTML5 ppl it not any interactivity regarding web2.0 EVER in websites 
U serve them the site in a static way and would not start update the clients when 
there not an reason like sharing items or something. When you do a refresh it is again a static page iwth static data served and there never an TCP or UDP http connection open and ALL first u send a REQUEST and then u get for this request an answer and the incomming is actually wrapped and bound to the OUTGOING request ALWAYS concerning firewall setups like windows has always open incoming for all.

Setup System
a. Install ruby -> i.e. mise
b. install bundler and jekyll gem

setuprepository
1. git clone https://github.com/mitvitaminen/fratzengeballer.eu.git
2. cd fratzengeballer.eu
3. bundle install
4. bundle exec jekyll serve
5. open the IP:Port specified by command line for preview on localmachine


