# Blogger Foo

Its a repo of Blogger _Foo_ website.

# How to get your own blogging website

1. Clone it
  ```
  git clone https://github.com/bloggerfoo/bloggerfoo.github.io myblog
  ```

2. Enter into the directory
  ```
  cd myblog
  ```

3. Replace content of following pages as your need:
    1. `_config.yml`
    2. `_data/about.yml`
    3. `_data/home.yml`
    4. `_data/projects.yml`
    5. `_posts`: Delete existing and write your own post in 
       [Jekyll format](https://jekyllrb.com/docs/step-by-step/08-blogging/){:target="_blank"}

4. Commit your changes
5. Create GitHub repo as `<your-github-username>.github.io`
6. Remove existing `origin`
  ```
  git remote remove origin
  ```

7. Add your newly created repo as `origin`
  ```
  git remote add origin git@github.com:<your-github-username>/<your-github-username>.github.io.git
  ```

8. Push the changes
  ```
  git push -u origin master
  ```

9. Visit your blogging website at `https://<your-github-username>.github.io`.
10. Enjoyee! :smile:
