| scrote

## usage

In your Makefile:

```
include node_modules/scrote-dev/Makefile

test-local:
    $(MOCHA) t
```

### scss

To process scss make a directory **assets/stylesheets/** with the file `app.scss`

### rendered output

Everything is rendered into `public` directory.
