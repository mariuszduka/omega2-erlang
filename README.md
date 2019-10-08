# Erlang/OTP for Omega2

Erlang/OTP version: **17.5**

**Highlights**  
Compiler: `erlc`  
Libraries:  
`asn1-3.0.4`, `common_test-1.10`, `compiler-5.0.4`, `cosEvent-2.1.15`, `cosEventDomain-1.1.14`, `cosFileTransfer-1.1.16`, `cosNotification-1.1.21`, `cosProperty-1.1.17`, `cosTime-1.1.14`, `cosTransactions-1.2.14`, `crypto-3.5`, `debugger-4.0.3`, `dialyzer-2.7.4`, `diameter-1.9`, `edoc-0.7.16`, `eldap-1.1.1`, `erl_docgen-0.3.7`, `erl_interface-3.7.20`, `erts-6.4`, `et-1.5`, `eunit-2.2.9`, `gs-1.5.16`, `hipe-3.11.3`, `ic-4.3.6`, `inets-5.10.6`, `kernel-3.2`, `megaco-3.17.3`, `mnesia-4.12.5`, `observer-2.0.4`, `orber-3.7.1`, `os_mon-2.3.1`, `ose-1.0.2`, `otp_mibs-1.0.10`, `parsetools-2.0.12`, `percept-0.8.10`, `public_key-0.23`, `reltool-0.6.6`, `runtime_tools-1.8.16`, `sasl-2.4.1`, `snmp-5.1.1`, `ssh-3.2`, `ssl-6.0`, `stdlib-2.4`, `syntax_tools-1.6.18`, `test_server-3.8`, `tools-2.7.2`, `typer-0.9.8`, `webtool-0.8.10`, `wx-1.3.3`, `xmerl-1.3.7`

## About Erlang/OTP

**OTP** is a set of Erlang libraries, which consists of the **Erlang** runtime system, a number of ready-to-use components mainly written in Erlang, and a set of design principles for Erlang programs. [Learn more about Erlang and OTP](http://erlang.org/doc/system_architecture_intro/sys_arch_intro.html).

Erlang/OTP is released under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

## Requirements

The package requires a minimum of 120 MB of flash storage.  
See instructions: [Booting from External Storage](https://docs.onion.io/omega2-docs/boot-from-external-storage.html)

## Installation

Download the repo:
```
git clone https://github.com/mariuszduka/omega2-erlang.git
```

and install package:
```
opkg install omega2-erlang/mipsel_24kc/erlang_17.5_full_mipsel_24kc.ipk
```

The package will be installed in the directory `/usr/local`.

Done!

## Usage

In the repo directory, execute the commands:

```
/usr/local/bin/erlc omega2.erl
/usr/local/bin/erl -noshell -s omega2 start -s init stop
```

See also [XMPP (Jabber) server for Omega2](https://github.com/mariuszduka/omega2-ejabberd)

## Resources

 * [Erlang/OTP official homepage](https://www.erlang.org/)
 * [Erlang/OTP on Github](https://github.com/erlang/otp)

## License

MIT License

Copyright (c) 2019 Mariusz Duka

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.