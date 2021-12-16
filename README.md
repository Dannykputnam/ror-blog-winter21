# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...




         index 
           |
           App (nav routes)
Home   About  Blogs     NoMatch 
              /\
   (new)BlogForm BlogList
                    \
            (own page) Blog (update, delete)
                      (update) BlogForm
                       |
                       Posts
            PostForm       PostList 
                           Post 
                           (update) PostForm
                           |
                           Comments
                  Commentform CommentList 
                            Comments
                              (update) CommentForm


                   