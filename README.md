# Nginx Log Highlighting

A Sublime Text 3 package that adds support for NGINX access log syntax highlighting.

The expected format is:

`remote_addr` `-` `remote_user` `[time_local]` "`request_verb` `request_endpoint` `request_result`" `status` `body_bytes_sent` "`http_referer`" "`http_user_agent`" "`http_x_forwarded_for`"

Where the three `http*` elements after `body_bytes_sent` are optional
## TO-DO

  - [ ] Add support for other log formats (or a custom format)
  - [ ] Add theme file and/or example color scheme definitions
