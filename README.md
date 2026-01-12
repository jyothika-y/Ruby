# Ruby
# Ruby on Rails Setup Guide

##  Objective

- To install Ruby and Rails successfully.  
- To verify installations using command-line tools.  
- To create and run a sample Rails application.
  
##  Step 1: Install Ruby

Download and install Ruby from the official Ruby Installer website:
Ruby Installer for Windows(https://rubyinstaller.org/downloads/)
Once installed, verify Ruby installation using:
  ruby -v
If Ruby is installed correctly, it will display the version:
  ruby 3.4.8 (2025-12-17 revision 995b59f666) +PRISM [x64-mingw-ucrt]

##  Step 2: Install Rails

Install Rails using the RubyGems package manager:
  gem install rails
After installation, verify Rails using:
  rails -v
If Rails is installed correctly, it will display something like:
  Rails 8.1.2

##  Step 3: Create a New Rails Project

To create a new Rails application, run:
  rails new ApplicationName

##  Step 4: Run the Rails Application

Navigate into your project folder:
  cd ApplicationName
Start the Rails server:
  rails s
Once the server starts, open your browser and go to:
  http://localhost:3000
You should see the default Rails welcome page
