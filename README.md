This is a demo app to try to reproduce the issues that would be fixed by
https://github.com/facebook/react/pull/7968.

I *think* I’ve configured Jest to emulate a similar setup to what those inside
FB may experience with Haste modules.

* `jest` is okay with this
* `flow` throws a lot of errors like
  `[modulename]. Duplicate module provider current provider. See: node_modules/react-dom/lib/[modulename].js`

