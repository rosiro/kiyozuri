# kiyozuri
Kiyozuri 
Open-Source Content Management System.  
create static websites.  
 - Compress HTML and CSS,javascript.
 - Static Exporting
 - majika
# Formats
supportt markdown, text-file, html-file and Perl script

## command
    // generate config.yaml mkdir tempaltes,source
    $ perl kiyozuri.pl init 
    
    // build. markdown file to static files. generate /public/ dir
    $ perl kiyozuri.pl build
    
    // webserver
    $ perl kiyozuri.pl server 
    
    // search
    $ perl kiyozuri.pl search "hoge"
    
    // replace
    $ perl kiyozuri.pl replace "hoge" "moge"
    

## Structure
example


    config.yaml 
    kiyozuri.pl 
    /lib/ 
        kiyozuri.pm 
        /kiyozuri/ 
    /db/ 
       /file/ 
       /sql/ 
    /templates/ 
        index.tmpl 
        categorylist.tmpl 
        singlepage.tmpl 
    /source/ 
        index.md 
        /perl/ 
            index.md 
            perl.md 
        /food/ 
            index.md 
            fish.md 
            beef.md 
    /public/ 
        index.html 
        /perl/ 
            index.html 
            perl.html 
        /food/ 
            index.html 
            fish.html 
            beef.html 

## config.yaml
## templates 
## source 
supportt markdown, text-file, html-file and Perl script 
## Converter


