# wec-ruby1011
##実行ログ
asadatomoki:~/workspace $ mkdir wec-ruby1011
asadatomoki:~/workspace $ mkdir wec-ruby1011
asadatomoki:~/workspace $ cd wec-ruby1011                                                                                                           
asadatomoki:~/workspace/wec-ruby1011 $ echo "# wec-ruby1011" >> README.md
asadatomoki:~/workspace/wec-ruby1011 $ git init
Initialized empty Git repository in /home/ubuntu/workspace/wec-ruby1011/.git/
 README.mdasadatomoki:~/workspace/wec-ruby1011 (master) $ git commit -m "first commit"[master (root-commit) d1e65a5] first commit
asadatomoki:~/workspace $ mkdir wec-ruby1011
asadatomoki:~/workspace $ cd wec-ruby1011                                                                                                              asadatomoki:~/workspace/wec-ruby1011 $ echo "# wec-ruby1011" >> README.mdasadatomoki:~/workspace/wec-ruby1011 $ git init
Initialized empty Git repository in /home/ubuntu/workspace/wec-ruby1011/.git/
asadatomoki:~/workspace/wec-ruby1011 (master) $ git add README.md
asadatomoki:~/workspace/wec-ruby1011 (master) $ git commit -m "first commit"
asadatomoki:~/workspace $ mkdir wec-ruby1011
asadatomoki:~/workspace $ cd wec-ruby1011                                                                                                           
asadatomoki:~/workspace/wec-ruby1011 $ echo "# wec-ruby1011" >> README.md
asadatomoki:~/workspace/wec-ruby1011 $ git init
Initialized empty Git repository in /home/ubuntu/workspace/wec-ruby1011/.git/
asadatomoki:~/workspace/wec-ruby1011 (master) $ git add README.md
asadatomoki:~/workspace/wec-ruby1011 (master) $ git commit -m "first commit"
[master (root-commit) d1e65a5] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
asadatomoki:~/workspace/wec-ruby1011 (master) $ git remote add origin https://github.com/asadatomoki/wec-ruby1011.git
asadatomoki:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Username for 'https://github.com': sudo gem install pry
Password for 'https://sudo gem install pry@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/asadatomoki/wec-ruby1011.git/'
asadatomoki:~/workspace/wec-ruby1011 (master) $ irb
2.4.0 :001 > 1+1
 => 2 
2.4.0 :002 > 1+1.0
 => 2.0 
2.4.0 :003 > 2.1+3+1
 => 6.1 
2.4.0 :004 > quit
asadatomoki:~/workspace/wec-ruby1011 (master) $ sudo gem install pry
Fetching: coderay-1.1.2.gem (100%)
Successfully installed coderay-1.1.2
Fetching: method_source-0.9.0.gem (100%)
Successfully installed method_source-0.9.0
Fetching: pry-0.11.1.gem (100%)
Successfully installed pry-0.11.1
3 gems installed
asadatomoki:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> quit
asadatomoki:~/workspace/wec-ruby1011 (master) $ bundle
bash: bundle: command not found
asadatomoki:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> puys "hello"
NoMethodError: undefined method `puys' for main:Object
Did you mean?  puts
from (pry):1:in `__pry__'
=> nil
[3] pry(main)> quit
asadatomoki:~/workspace/wec-ruby1011 (master) $ sudo gem install bundle
Fetching: bundler-1.15.4.gem (100%)
Successfully installed bundler-1.15.4
Fetching: bundle-0.0.1.gem (100%)
2 gems installed
asadatomoki:~/workspace/wec-ruby1011 (master) $ sudo gem install bundler
Successfully installed bundler-1.15.4
1 gem installed
asadatomoki:~/workspace/wec-ruby1011 (master) $ bundle init
Writing new Gemfile to /home/ubuntu/workspace/wec-ruby1011/Gemfile
asadatomoki:~/workspace/wec-ruby1011 (master) $ gem "nokogiri"
ERROR:  While executing gem ... (Gem::CommandLineError)
    Unknown command nokogiri
asadatomoki:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Resolving dependencies...
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
asadatomoki:~/workspace/wec-ruby1011 (master) $ gem "nokogiri"
ERROR:  While executing gem ... (Gem::CommandLineError)
    Unknown command nokogiri
asadatomoki:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
asadatomoki:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
asadatomoki:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
asadatomoki:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> require "nokogiri"
LoadError: cannot load such file -- nokogiri
from /usr/local/rvm/rubies/ruby-2.4.0/lib/ruby/2.4.0/rubygems/core_ext/kernel_require.rb:55:in `require'
[2] pry(main)> 
asadatomoki:~/workspace/wec-ruby1011 (master) $ bundle install
Fetching gem metadata from https://rubygems.org/.............
Fetching version metadata from https://rubygems.org/.
Resolving dependencies...
Using bundler 1.15.4
Using bundler 1.15.4
Fetching mini_portile2 2.3.0
Installing mini_portile2 2.3.0
Fetching nokogiri 1.8.1
Installing nokogiri 1.8.1 with native extensions
Bundle complete! 1 Gemfile dependency, 3 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.asadatomoki:~/workspace/wec-ruby1011 (master) $ ruby nokogiri.rb
"神戸電子専門学校｜IT・Web・グラフィックデザイン・ゲームクリエイターに強い専門学校"
asadatomoki:~/workspace/wec-ruby1011 (master) $ git add *
asadatomoki:~/workspace/wec-ruby1011 (master) $ git commit -m '10/11　実行ログ
> git push
> git commit -m '10/11　実行ログ
git push