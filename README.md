#Todo
A simple to-do app using the Ember CLI

## Source
A tutorial from `http://thetechcofounder.com/getting-started-with-ember-js-using-ember-cli/`,
one of the few I could find.

Note: Ember 2.0 is coming, so this works for now, but may be broken in the near future.

## Security
I deleted `”ember-cli-content-security-policy”: “0.4.0”` from `package.json` to get the
functionality working, but this is less than ideal. See `https://github.com/rwjblue/ember-cli-content-security-policy`
for whitelisting process
