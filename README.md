# contract-wt

A Python WebTransport client that tests the engine's HTTP/3 WebTransport server from an independent implementation.

## What it is for

A Godot client talking to a Godot server agrees with itself about anything both ends get wrong. This client is written from the specification instead, and holds several sessions open at once to exercise the server's roster of connected peers. [RFD 2123](https://github.com/V-Sekai-fire/manuals-weftspun/blob/main/rfd/2123-a-second-webtransport-implementation.exs) owns the design.

## Run

    pip install -r requirements.txt
    python roster_client.py --help

Point it at the WebTransport server demo, `modules/http3/demo/wt_server_demo.gd` in `entities-godot`.

## Licence

MIT. See [LICENSE](LICENSE).
