# Create a stream

You can create a stream using Zulip's REST API by submitting a
[subscribe](/api/subscribe) request with a stream name that
doesn't yet exist.  You can specify the initial configuration of the
stream using the `invite_only` and `announce` parameters to that
request.
