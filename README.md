# Hubslurp

[Peril](https://github.com/rackerlabs/peril) slurper to watch GitHub issues
on selected projects, that mention selected keywords.

## To Develop

If you want to hack on hubslurp:

```bash
cd ${PROJECTS_HOME}
git clone git@github.com:rackerlabs/hubslurp.git
cd hubslurp

# You'll need to fill in a few configuration options.
cp config.yml.example config.yml
${EDITOR} config.yml

# Install dependencies
bundle install

# Kick it off. Logs go to stdout. Ctrl-C to kill it.
bundle exec ruby hubslurp.rb
```
