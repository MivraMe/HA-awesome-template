# HA-awesome-template
This repository is inspired by [domo-quebec](https://github.com/domo-quebec), which is a repository featuring awesome templates for the Quebec province in Canada.

### Here, you will find a variety of sensors that can be integrated with Home Assistant using the ["package"](https://www.home-assistant.io/docs/configuration/packages/) method. ⚠However, this method requires a little configuration:⚠️

# Configuration

First, you will need to add a ``packages`` folder in your Home Assistant configuration directory:

```
config/
  packages/
    example_packages.yaml
    example_package2.yaml
```

After, you will need to add this to your `configuration.yaml` file:
```yaml
homeassistant:
  packages: !include_dir_named packages
```

The initial configuration is now complete, and you are ready to add your first package!

# Contribution Guidelines

There are two ways you can contribute:

- If you've discovered a data source that might interest us, please open an issue.
- If you have a package that is ready and functional, feel free to open a pull request.

When opening a pull request, please ensure that you follow the [example](example) structure.

# Supported sources

| Soource | Description |
|-|-|
| AAA | Custom |
