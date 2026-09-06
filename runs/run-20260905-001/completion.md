**Benchmark run `run-20260905-001` FAILED** after 22h33m on `obelisk`.


> running-ng failed (exit 1); console tail: tive_emitter.finalize()
                     ^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/udesou/.bench-agent/git/running-ng/src/running/contract/native.py", line 237, in finalize
    emit.write_json(str(self.dir / "manifest.json"), man)
  File "/home/udesou/.bench-agent/git/running-ng/src/running/contract/emit.py", line 196, in write_json
    json.dump(obj, f, indent=2)
  File "/usr/lib/python3.12/json/__init__.py", line 180, in dump
    fp.write(chunk)
OSError: [Errno 28] No space left on device
X

[Results](https://udesou.info/ocaml-bench-results/run.html#run-20260905-001) -- measurements, dashboard, logs.
