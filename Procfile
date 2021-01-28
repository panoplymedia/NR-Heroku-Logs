web: bundle exec fluentd -vv --use-v1-config -c fluent.conf -i "<source>\n @type heroku_http\n port $PORT\n <parse>@type none</parse></source>"
