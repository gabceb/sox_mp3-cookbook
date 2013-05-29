sox_mp3 Cookbook
================

Install [Sox](http://sox.sourceforge.net/) with mp3 support

Requirements
------------

#### packages
- `apt` - sox_mp3 needs apt to install packages.

This cookbook has only been tested on Ubuntu 12.04. 

Attributes
----------

e.g.
#### sox_mp3::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['sox_mp3']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

Usage
-----
#### sox_mp3::default

Include `sox_mp3` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[sox_mp3]"
  ]
}
```

Contributing
------------

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write you change
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Gabriel Cebrian
