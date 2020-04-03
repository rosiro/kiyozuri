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
    $ perl kiyozuri.pl init // generate config.yaml mkdir tempaltes,source
    $ perl kiyozuri.pl build // build html static files
    $ perl kiyozuri.pl server // webserver

## Structure
example


    config.yaml 
    kiyozuri.pl 
    /lib/ 
        kiyozuri.pm 
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

## config.yaml
## templates 
## source 
supportt markdown, text-file, html-file and Perl script 
## Converter


