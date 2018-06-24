# Ckeditor Plugin

**This README.md file should be modified to describe the features, installation, configuration, and general usage of this plugin.**

The **Ckeditor** Plugin is for [Grav CMS](http://github.com/getgrav/grav). ckeditor

## Installation

Installing the Ckeditor plugin can be done in one of two ways. The GPM (Grav Package Manager) installation method enables you to quickly and easily install the plugin with a simple terminal command, while the manual method enables you to do so via a zip file.

### GPM Installation (Preferred)

The simplest way to install this plugin is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install ckeditor

This will install the Ckeditor plugin into your `/user/plugins` directory within Grav. Its files can be found under `/your/site/grav/user/plugins/ckeditor`.

### Manual Installation

To install this plugin, just download the zip version of this repository and unzip it under `/your/site/grav/user/plugins`. Then, rename the folder to `ckeditor`. You can find these files on [GitHub](https://github.com/jmolivas/grav-plugin-ckeditor) or via [GetGrav.org](http://getgrav.org/downloads/plugins#extras).

You should now have all the plugin files under

    /your/site/grav/user/plugins/ckeditor
	
> NOTE: This plugin is a modular component for Grav which requires [Grav](http://github.com/getgrav/grav) and the [Error](https://github.com/getgrav/grav-plugin-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) to operate.

### Admin Plugin

If you use the admin plugin, you can install directly through the admin plugin by browsing the `Plugins` tab and clicking on the `Add` button.

## Configuration

Before configuring this plugin, you should copy the `user/plugins/ckeditor/ckeditor.yaml` to `user/config/plugins/ckeditor.yaml` and only edit that copy.

Here is the default configuration and an explanation of available options:

```yaml
enabled: true
```

Note that if you use the admin plugin, a file with your configuration, and named ckeditor.yaml will be saved in the `user/config/plugins/` folder once the configuration is saved in the admin.

## Usage

**Describe how to use the plugin.**

## Credits

This project use [CKEditor 5](https://ckeditor.com/ckeditor-5/) A set of ready to use rich text editors created with a powerful framework.

## To Do

- [ ] Add usage instructions
- [ ] Add Markdown support
- [ ] Add configurable options
- [ ] Add configurable label for fields
