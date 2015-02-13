# Erlang Action Pack

A complete package of [Erlang/OTP][], [Elixir][], and [Phoenix][] to quickly set up a local Web development environment, based on current versions of each package used.

[Phoenix][] also includes [Cowboy][], and its dependencies.

## Notes

 * Currently only [Erlang/OTP][], and [Elixir][] are installed!
 * [Phoenix][] is in it's very early stage, only on the feature branch.
 * Currently only tested on Ubuntu 14.04 (x86_64, armv7l) and Raspbian (Raspberry 2)
 * No editor plugins will be installed!
   It is up to You which editor You want to use.


## Setup

```bash
./scripts/eap setup modules
./scripts/eap setup erlang
./scripts/eap setup elixir
./scripts/eap setup eap
```


## Usage

After the setup is finished, You can try the following:

```bash
source ~/.eap/etc/environment
```

This call modifies the ```PATH``` and ```MANPATH``` environment variables.

Now ```erl```, ```iex```, and ```mix``` should work.


## Links

 * Project Web Sites
   * [Erlang/OTP](http://erlang.org/)
   * [Elixir](http://elixir-lang.org/)
   * [Phoenix](http://www.phoenixframework.org/)
 * Editor Plugins
   * [Emacs major mode for Elixir](https://github.com/elixir-lang/emacs-elixir)
   * [Vim configuration files for Elixir](https://github.com/elixir-lang/vim-elixir)
   

[Erlang/OTP]:	https://github.com/erlang/otp
[Elixir]:	https://github.com/elixir-lang/elixir
[Cowboy]:	https://github.com/ninenines/cowboy
[Ranch]:	https://github.com/ninenines/ranch
[Bullet]:	https://github.com/extend/bullet
[Sheriff]:	https://github.com/extend/sheriff
[erlang.mk]:	https://github.com/ninenines/erlang.mk
[Phoenix]:	https://github.com/phoenixframework/phoenix


