# xfabian.github.io

Source of my personal website, [xfabian.github.io](https://xfabian.github.io).

Built with Jekyll on [AcademicPages](https://github.com/academicpages/academicpages.github.io), a fork of the
[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme (MIT License, see `LICENSE`).

## Running locally

```
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml --livereload
```

Then open http://localhost:4000.
