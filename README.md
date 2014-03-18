OctoMap Cookbook
================

This cookbook will install OctoMap an efficient probabilistic 3D mapping framework based on octrees.

[![Build Status](http://ci.devrt.tk/job/chef-octomap/badge/icon)](http://ci.devrt.tk/job/chef-octomap/)

Requirements
------------

- `build-essential` - OctoMap requires c++ compiler.
- `git` - OctoMap requires git.
- `cmake` - OctoMap requires cmake.

Attributes
----------

No attributes yet.

Usage
-----

Just include `octomap` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[octomap]"
  ]
}
```

Contributing
------------

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------

Apache 2.0

Author: Yosuke Matsusaka
