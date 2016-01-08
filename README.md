# chef-wrapper-users-cookbook

Wrapper cookbook for creating users on servers.

## Supported Platforms

Ubuntu 14.04

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['chef-wrapper-users']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### chef-wrapper-users::default

Include `chef-wrapper-users` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[chef-wrapper-users::default]"
  ]
}
```

## License and Authors

Author:: Cobus Bernard (<me@cobus.io>)
