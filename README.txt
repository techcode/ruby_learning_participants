RubyLearning.org Participants' Countries

Now three tools available.
- ruby_launcher.rb   : Launches Shoes app, shoes_countries_new.rb. Specify the course name.
- ruby_launcher2.rb  : Launches Shoes app, shoes_all_courses.rb. Total of all courses.
- all_courses.rb     : No Shoes. Just output to console. Total of all courses.

Requirement:
  This vesion uses Hpricot and Mechanize (0.9.0).

  gem install hpricot
  gem install mechanize

Usage:
- replace your username and passowrd
  + line 12 and 13 of ruby_launcher.rb
  + line 17 and 18 of ruby_launcher2.rb
  + line 20 and 21 of all_courses.rb

- select the courses
  + ruby_launcher.rb  : give it as an argument
  + ruby_launcher2.rb : edit line 6, 7, 8, 9
  + all_courses.rb    : edit line 7, 8, 9, 10

- run the Ruby program
  + C:\> ruby ruby_launcher.rb <course name>
  + C:\> ruby ruby_launcher2.rb
  + C:\> ruby all_courses.rb

Change log:
12th Feb: Merged RLGGHC's pull-request.
28th Jan: Added two new tools, ruby_launcher2.rb and all_courses.rb, which output a total of all courses.
11th Jan: Supported the new spec of Mechanize 0.9.0.
2009
16th Oct: Added 'nostroke' for Shoes-0.r1057
13th Oct: Released new ruby_launcher.rb and shows_countries_new.rb
          This new version needs no local data files (i.e. forpc101-7c.html)
          It will directly access to the web site (http://rubylearning.org/class/login/index.php)

To do list:
- If the following Shoes feature works well, use it instead of the way launching from ruby.

  Shoes.setup do
    gem 'mechanize'
  end

--------------------------------------------------------------------
The OLD version:

Usage is:
- run Countries/shoes_countries.rb with Shoes
- open the ask_open_file window
- select Countries/xxxx.html file
- show the list of the Participants' Countries

Change log:
10th Oct: Updated data files (forpc101-7c.html and forpc101-8c.html)
--------------------------------------------------------------------

Cheers,
ashbb (Satoshi Asakawa)

Cheers,
Ed O'Neill
Again...a great little course!

