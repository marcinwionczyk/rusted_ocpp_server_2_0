# rusted_ocpp_server_2_0
OCPP Server based on actix-web framework (backend), yew (frontend).
It's based on <a href="https://github.com/security-union/yew-actix-template" taget="_blank">yew-actix-template</a>

# Specification
This server is going to use [OCPP protocol 2.0.1](https://www.openchargealliance.org/protocols/ocpp-201/) to communicate with chargers in order to test chargers behavior. 

I want to learn some new ways of web development and for now I do this for fun.

 Yew  + Actix Full Stack Template
<p align="center">
  <img src="https://user-images.githubusercontent.com/1176339/177201719-cd387dae-fdd0-4237-90ec-f140fcfcb49c.png" >
</p>

Contains 3 sub-projects

1. actix-api: actix web server
2. yew-ui: Yew frontend
3. types: json serializable structures used to communicate the frontend and backend.

Execute `./start_dev.sh` to start all components.

Do a code change to to the yew-ui, types or actix-api and see how everything reloads.

# Prerequisites

1. Install rust, cargo and friends. Please watch this video for more details: https://youtu.be/nnuaiW1OhjA
https://doc.rust-lang.org/cargo/getting-started/installation.html

2. Install trunk and `target add wasm32-unknown-unknown` please watch this video for more details: https://youtu.b>
```
cargo install --locked trunk
target add wasm32-unknown-unknown
```

3. Install cargo watch
```
cargo install cargo-watch
```
