# Simpletest

We are moving to [simpletest/simpletest](https://github.com/simpletest/simpletest).
The composer packages have also been updated.

To get your project up-to-date with these changes, it is recommended to execute following command in your project's directory.

```
find ./ -type f -exec sed -i 's:vierbergenlars/simpletest:simpletest/simpletest:g' {} \;
```

This will find and replace `vierbergenlars/simpletest` with `simpletest/simpletest` everywhere.
