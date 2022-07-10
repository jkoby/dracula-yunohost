### [YunoHost](https://yunohost.org)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/yunohost.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/foobar/archive/master.zip) option and unzip them.

#### Activating theme

1. Copy the dracula folder from this repository into `/usr/share/ssowat/portal/assets/themes/`
2. Edit `/etc/ssowat/conf.json.persistent` and set the `theme` to `dracula`:

```
{
    "theme": "dracula"
}

```
3. Changes take effect immediately, but clients may need to force-reload to see them. (Ctrl-Shift-R in the browser)

