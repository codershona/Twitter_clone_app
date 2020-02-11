# README

### PROJECT : TWITTER CLONE APP USING RAILS 5.


#### READY TO DELPOY IN HEROKU


* NOTES: 
```
   First steps: 
      - rails g scaffold Tweeet tweeet:text ;
      - added gems in gemfile and run bin/bundle ;
      - guard init livereload ;
      - rails generate simple_form:install ;
      - rails generate devise:install ,
      -  bundle exec guard ;
      - rails g devise User ;
      - rails g migration AddFieldsToUsers ;
      - rails g migration AddUserIdToTweeets user_id:integer 

      - rails c ( @user = User; @user; @tweeet = Tweeet; @user.last; @user = @user.last ;@user.destroy;@user = User;@user.all;) ;

```
