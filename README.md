### Local development

Tested with `rbenv`, Ruby version `3.1.3`.
- ```bash
  brew install rbenv ruby-build
  rbenv init
  eval "$(rbenv init - zsh)"
  rbenv install 3.1.3
  rbenv shell 3.1.3
  ```

- [Install Jekyll](https://jekyllrb.com/).
  ```bash
  gem install bundler jekyll
  bundle install
  ```

- Then
  ```
  bundle exec jekyll serve
  ```
  ==> [http://127.0.0.1:4000/s2024/](http://127.0.0.1:4000/s2024/)

### Important Files
- `_data/course_info.yml`
- `_data/schedule.yml`
- `_layouts/home.yml`
- `_layouts/schedule.yml`

### Acknowledgements
This template is derived from [kazemnejad.github.io/jekyll-course-website-template/](https://kazemnejad.github.io/jekyll-course-website-template/).
