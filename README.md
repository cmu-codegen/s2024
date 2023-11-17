### Local development

Tested with `rbenv`, Ruby version `2.7.6`.
- ```bash
  rbenv init
  eval "$(rbenv init - zsh)"
  rbenv shell 2.7.6
  ```

- [Install Jekyll](https://jekyllrb.com/).

- In `_config.yml`, set:
  ```
  baseurl: "" 
  url: "http://localhost" 
  ```
Then:
```
bundle exec jekyll serve
```

### Important Files
- `_data/course_info.yml`
- `_data/schedule.yml`
- `_layouts/home.yml`
- `_layouts/schedule.yml`

### Acknowledgements
This template is derived from [kazemnejad.github.io/jekyll-course-website-template/](https://kazemnejad.github.io/jekyll-course-website-template/).
