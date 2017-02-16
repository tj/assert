# assert

Assertion pkg for Go, copied from https://github.com/stretchr/testify's require package.

I find early errors more useful than the `t.Errorf()` calls, which often fall through to nil pointers causing panics etc.
