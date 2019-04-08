# rust-diesel-cli-blog
An demo to see how to make a cli for doing CRUD against a postgres db.


# how to run

expects a postgress db to accessable locally on port 5432. There is a docker image in the repo to spin up.

### To show posts
```cargo run --bin show_posts ```

### To add a post
```cargo run --bin create_posts ```

### To update / publish posts
```cargo run --bin publish_posts (id) ```

### To delete posts 
```cargo run --bin delete_posts (id) ```
