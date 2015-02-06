# Erlang Action Pack

A complete package of [Erlang/OTP][], [Elixir][], [Cowboy][], and [Phoenix][] to quickly set up a local Web development environment, based on current versions of each package used.
[Cowboy][] also includes [Ranch][], [Bullet][], [Sheriff][], and [erlang.mk][].

## Notes

 * Currently only [Erlang/OTP][], and [Elixir][] are installed!
 * No editor plugins will be installed!

## Setup

```bash
./scripts/eap setup modules
./scripts/eap setup erlang
./scripts/eap setup elixir
./scripts/eap setup eap
```

## Usage

```bash
source ~/.eap/etc/environment
```

This call modifies the ```PATH``` and ```MANPATH``` environment variables.

## Links

 * Project Web Sites
   * [Erlang/OTP](http://erlang.org)
   * [Elixir](http://elixir-lang.org/)
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


