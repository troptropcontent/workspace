ARG VARIANT=3.1-bullseye
FROM mcr.microsoft.com/vscode/devcontainers/ruby:${VARIANT}

RUN gem install rails 
ENV RAILS_DEVELOPMENT_HOSTS=".githubpreview.dev,.app.github.dev,.preview.app.github.dev"
